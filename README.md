# sveltekit-storybook

```text
pnpm storybook

> svelte-kit-js@0.0.1 storybook /Users/Jerry/Developer/svelte-kit-js
> storybook dev -p 6006

@storybook/core v8.4.7

SB_CORE-SERVER_0002 (CriticalPresetLoadError): Storybook failed to load the following preset: ./.storybook/main.js.

Please check whether your setup is correct, the Storybook dependencies (and their peer dependencies) are installed correctly and there are no package version clashes.

If you believe this is a bug, please open an issue on Github.

SB_CORE-SERVER_0002 (CriticalPresetLoadError): Storybook failed to load the following preset: ./node_modules/.pnpm/@storybook+addon-svelte-csf@5.0.0-next.14_@storybook+svelte@8.4.7_storybook@8.4.7_prettier@3._6qdorkd3udyipaxdzmyhkuxaka/node_modules/@storybook/addon-svelte-csf/dist/preset.js.

Please check whether your setup is correct, the Storybook dependencies (and their peer dependencies) are installed correctly and there are no package version clashes.

If you believe this is a bug, please open an issue on Github.

Error [ERR_UNSUPPORTED_DIR_IMPORT]: Directory import './node_modules/.pnpm/@storybook+addon-svelte-csf@5.0.0-next.14_@storybook+svelte@8.4.7_storybook@8.4.7_prettier@3._6qdorkd3udyipaxdzmyhkuxaka/node_modules/@storybook/addon-svelte-csf/dist/compiler/post-transform/story' is not supported resolving ES modules imported from ./node_modules/.pnpm/@storybook+addon-svelte-csf@5.0.0-next.14_@storybook+svelte@8.4.7_storybook@8.4.7_prettier@3._6qdorkd3udyipaxdzmyhkuxaka/node_modules/@storybook/addon-svelte-csf/dist/compiler/post-transform/index.js
    at finalizeResolution (node:internal/modules/esm/resolve:263:11)
    at moduleResolve (node:internal/modules/esm/resolve:932:10)
    at defaultResolve (node:internal/modules/esm/resolve:1056:11)
    at ModuleLoader.defaultResolve (node:internal/modules/esm/loader:654:12)
    at #cachedDefaultResolve (node:internal/modules/esm/loader:603:25)
    at ModuleLoader.getModuleJobForRequire (node:internal/modules/esm/loader:353:53)
    at new ModuleJobSync (node:internal/modules/esm/module_job:341:34)
    at ModuleLoader.getModuleJobForRequire (node:internal/modules/esm/loader:413:11)
    at new ModuleJobSync (node:internal/modules/esm/module_job:341:34)
    at ModuleLoader.getModuleJobForRequire (node:internal/modules/esm/loader:413:11)

More info:

    at loadPreset (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/common/index.cjs:16477:13)

More info:

    at loadPreset (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/common/index.cjs:16477:13)
    at async Promise.all (index 1)
    at async loadPresets (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/common/index.cjs:16487:55)
    at async getPresets (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/common/index.cjs:16520:11)
    at async buildDevStandalone (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/core-server/index.cjs:37145:11)
    at async withTelemetry (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/core-server/index.cjs:35757:12)
    at async dev (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/cli/bin/index.cjs:2591:3)
    at async s.<anonymous> (./node_modules/.pnpm/@storybook+core@8.4.7_prettier@3.4.2/node_modules/@storybook/core/dist/cli/bin/index.cjs:2643:74)

WARN Broken build, fix the error above.
WARN You may need to refresh the browser.

WARN   Failed to load preset: {"type":"presets","name":"/Users/Jerry/Developer/svelte-kit-js/node_modules/.pnpm/@storybook+addon-svelte-csf@5.0.0-next.14_@storybook+svelte@8.4.7_storybook@8.4.7_prettier@3._6qdorkd3udyipaxdzmyhkuxaka/node_modules/@storybook/addon-svelte-csf/dist/preset.js"} on level 1
Error [ERR_UNSUPPORTED_DIR_IMPORT]: Directory import './node_modules/.pnpm/@storybook+addon-svelte-csf@5.0.0-next.14_@storybook+svelte@8.4.7_storybook@8.4.7_prettier@3._6qdorkd3udyipaxdzmyhkuxaka/node_modules/@storybook/addon-svelte-csf/dist/compiler/post-transform/story' is not supported resolving ES modules imported from ./node_modules/.pnpm/@storybook+addon-svelte-csf@5.0.0-next.14_@storybook+svelte@8.4.7_storybook@8.4.7_prettier@3._6qdorkd3udyipaxdzmyhkuxaka/node_modules/@storybook/addon-svelte-csf/dist/compiler/post-transform/index.js
    at finalizeResolution (node:internal/modules/esm/resolve:263:11)
    at moduleResolve (node:internal/modules/esm/resolve:932:10)
    at defaultResolve (node:internal/modules/esm/resolve:1056:11)
    at ModuleLoader.defaultResolve (node:internal/modules/esm/loader:654:12)
    at #cachedDefaultResolve (node:internal/modules/esm/loader:603:25)
    at ModuleLoader.getModuleJobForRequire (node:internal/modules/esm/loader:353:53)
    at new ModuleJobSync (node:internal/modules/esm/module_job:341:34)
    at ModuleLoader.getModuleJobForRequire (node:internal/modules/esm/loader:413:11)
    at new ModuleJobSync (node:internal/modules/esm/module_job:341:34)
    at ModuleLoader.getModuleJobForRequire (node:internal/modules/esm/loader:413:11)
 ELIFECYCLE  Command failed with exit code 1.
```
