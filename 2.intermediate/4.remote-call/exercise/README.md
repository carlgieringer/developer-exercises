# 3. Remote Call Exercise

[Problem statement](https://holochain-gym.github.io/developers/intermediate/remote-call/)

## Exercise

- Open your IDE in [the zome](/intermediate/3.remote-call/zomes/exercise).
- Code all `unimplemented!()` functions.
- Compile and run the tests, and check that all tests are passing.

---

### Setup - nix-shell
IMPORTANT: You need to run these exercises in the correct nix-shell.
A nix-shell sets up all the right dependencies for the holochain-gym.

In the base folder of this repository, developer-exercises, you will find
a `default.nix` file. Run the following command in your terminal:

```bash
nix-shell
```
The very first time you run this, it will take long time, somewhere between 20 and 80 minutes.
This is because it will download, install and compile everything you need. After that it will only take a second or two to run.
Then you can build with:


### Testing

```bash
cd test
npm install
npm test
```
