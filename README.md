Testing memory and slowness with `jest.config.ts` files.

Run:

```shell
nx reset
nx show projects
```

This takes about 5 seconds locally for me.

Then checkout the `ts` branch and run the same commands. You'll run out of memory.

With this patch (https://github.com/nrwl/nx/pull/26807), it'll succeed but still take a long time.

