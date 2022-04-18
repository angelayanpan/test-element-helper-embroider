```
$ ember b --environment test

Build Error (PackagerRunner) in ../../components/foo-bar.hbs

Module build failed (from ../../../../../../../../../../Users/apan/Project/test-element-helper-embroider/node_modules/thread-loader/dist/cjs.js):
Thread Loader (Worker 0)
$TMPDIR/embroider/66c19e/components/foo-bar.hbs/foo-bar.hbs: Missing helper: element in $TMPDIR/embroider/66c19e/components/foo-bar.hbs

    at CompatResolver.dependenciesOf (/Users/apan/Project/test-element-helper-embroider/node_modules/@embroider/compat/src/resolver.js:252:33)
    at NodeTemplateCompiler.precompile (/Users/apan/Project/test-element-helper-embroider/node_modules/@embroider/core/src/template-compiler-common.js:61:42)
    at handleCalled (/Users/apan/Project/test-element-helper-embroider/node_modules/@embroider/core/src/babel-plugin-inline-hbs.js:75:39)
    at PluginPass.CallExpression (/Users/apan/Project/test-element-helper-embroider/node_modules/@embroider/core/src/babel-plugin-inline-hbs.js:44:29)
    at PluginPass.<anonymous> (/Users/apan/Project/test-element-helper-embroider/node_modules/@embroider/core/src/portable-babel-launcher.js:37:29)
    at newFn (/Users/apan/Project/test-element-helper-embroider/node_modules/@babel/traverse/lib/visitors.js:177:21)
    at NodePath._call (/Users/apan/Project/test-element-helper-embroider/node_modules/@babel/traverse/lib/path/context.js:53:20)
    at NodePath.call (/Users/apan/Project/test-element-helper-embroider/node_modules/@babel/traverse/lib/path/context.js:40:17)
    at NodePath.visit (/Users/apan/Project/test-element-helper-embroider/node_modules/@babel/traverse/lib/path/context.js:100:31)
    at TraversalContext.visitQueue (/Users/apan/Project/test-element-helper-embroider/node_modules/@babel/traverse/lib/context.js:103:16)


Stack Trace and Error Report: /var/folders/zx/zln4zlz96812ljx8xn1yg0c4001prb/T/error.dump.017bac67fd71923f1e6f0819414cbb19.log
```
