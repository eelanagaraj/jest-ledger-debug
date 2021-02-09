# Bug reproduction: interaction between jest and @ledgerhq/hw-transport-node-hid

In root of repository, run:

```sh
yarn && yarn test
```

The first test that is run will pass but the other will fail with the following result:

```sh
  ● Test suite failed to run

    TypeError: Cannot redefine property: configDescriptor
        at Function.defineProperty (<anonymous>)

```
