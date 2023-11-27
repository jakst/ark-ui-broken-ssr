1. Start the dev server `pnpm dev`
2. Go to `http://localhost:3000`
3. The following is printed to the console when opening the page:

```
app-index.js:32 Warning: Prop `id` did not match. Server: "menu::R2mukq::trigger" Client: "menu::R6mukq::trigger"
    at div
    at eval (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/factory.mjs:17:13)
    at eval (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/menu/menu-trigger-item.mjs:18:107)
    at Menu (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/menu/menu.mjs:50:86)
    at div
    at eval (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/factory.mjs:17:13)
    at eval (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/menu/menu-content.mjs:21:80)
    at div
    at eval (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/factory.mjs:17:13)
    at eval (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/menu/menu-positioner.mjs:21:80)
    at Portal (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/portal.mjs:16:11)
    at Menu (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/@ark-ui+react@1.1.0_@internationalized+date@3.5.0_react-dom@18.2.0_react@18.2.0/node_modules/@ark-ui/react/menu/menu.mjs:50:86)
    at MyMenu
    at div
    at InnerLayoutRouter (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/layout-router.js:240:11)
    at RedirectErrorBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/redirect-boundary.js:72:9)
    at RedirectBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/redirect-boundary.js:80:11)
    at NotFoundErrorBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/not-found-boundary.js:54:9)
    at NotFoundBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/not-found-boundary.js:62:11)
    at LoadingBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/layout-router.js:345:11)
    at ErrorBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/error-boundary.js:130:11)
    at InnerScrollAndFocusHandler (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/layout-router.js:151:9)
    at ScrollAndFocusHandler (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/layout-router.js:226:11)
    at RenderFromTemplateContext (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/render-from-template-context.js:15:44)
    at OuterLayoutRouter (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/layout-router.js:355:11)
    at body
    at html
    at RedirectErrorBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/redirect-boundary.js:72:9)
    at RedirectBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/redirect-boundary.js:80:11)
    at NotFoundErrorBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/not-found-boundary.js:54:9)
    at NotFoundBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/not-found-boundary.js:62:11)
    at DevRootNotFoundBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/dev-root-not-found-boundary.js:32:11)
    at ReactDevOverlay (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/react-dev-overlay/internal/ReactDevOverlay.js:66:9)
    at HotReload (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/react-dev-overlay/hot-reloader-client.js:295:11)
    at Router (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/app-router.js:169:11)
    at ErrorBoundaryHandler (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/error-boundary.js:100:9)
    at ErrorBoundary (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/error-boundary.js:130:11)
    at AppRouter (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/components/app-router.js:451:13)
    at ServerRoot (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/app-index.js:128:11)
    at RSCComponent
    at Root (webpack-internal:///(app-pages-browser)/./node_modules/.pnpm/next@14.0.3_react-dom@18.2.0_react@18.2.0/node_modules/next/dist/client/app-index.js:144:11)
```
