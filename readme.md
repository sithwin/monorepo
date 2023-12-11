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