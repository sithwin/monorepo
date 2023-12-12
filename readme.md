# Init
pnpm init

# Filter
pnpm --filter mono-app dev

# Create Shared folder
run pnpm init

# Install shared app
run pnpm add --filter shared-ui react
run pnpm add --filter shared-ui typescript -D

# Build
pnpm add --filter shared-ui build

# Add
pnpm add shared-ui --filter mono-app --workspace

# Install NX
pnpm add nx -D -w

# Run the package
npx nx build shared-ui
npx nx dev mono-app

# Add nx.json
npx nx build shared-ui
- add trgetDefults

# Task Depedency

# Get the graph
npx nx graph

# Build Command
 npx nx affected:build --base=origin/master~1 --head=origin/master

# Build all project
npx nx run-many --target=build --all