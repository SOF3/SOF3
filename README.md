### About Me

- **Rust**: Almost all my serious personal projects are written in Rust.
- **Type-driven**: I adopt type-driven development.
  I tend to express most code concepts with the type system.
  For example, I use newtype pattern extensively for basic numeric types,
  and assertions about types are expressed in wrapper types.
- **Plaintext only**: I avoid working with files that cannot be managed by Git.
  This means I avoid committing images
  (unless they won't be modified or in SVG) into a repo,
  and I don't like producing multimedia.
  - For documents, I use Markdown and LaTeX and generate the PDF on CI.
  - For graphs, I use GraphViz and compile the image on CI.
- **Vim**: My primary IDE is NeoVim + coc.nvim.
  On mobile, I develop with Vim over SSH.
  My setup is updated [here](https://github.com/SOF3/nvim-config).
- **Linux**: My personal computer runs on Ubuntu.
  I use Bash as the default shell.
  My setup is [here](https://github.com/SOF3/sys).
- Other preferences:
  - Scripting languages: Bash, Python and NodeJS.
  - JVM language: Kotlin.
  - Deployment: Docker on Alpine Linux image.

[![](https://github.com/SOF3/github-stats/raw/master/generated/overview.svg)](https://github.com/SOF3/github-stats)
[![](https://github-readme-stats.vercel.app/api?username=SOF3&theme=vue&show_icons=true&count_private=true&include_all_commits=true)](https://github.com/anuraghazra/github-readme-stats)

![](https://github-profile-trophy.vercel.app/?username=SOF3)

### Personal blog
I have started jotting down some weird opinions from me
in the [wiki](https://github.com/SOF3/SOF3/wiki) of this personal repo.

### Highlighted projects
I have started a lot of open-source projects for personal interest,
but many are incomplete because of lack of time and financial support.
Incomplete projects are marked as :hourglass_flowing_sand:.

Some of these projects were not created or maintained by me,
but I included them here as I have contributed a substantial amount of code to them.

#### General-purpose libraries
- [await-generator](https://github.com/SOF3/await-generator), a PHP library that enables async/await pattern
- [portrait](https://github.com/SOF3/portrait), a Rust proc-macro framework to write trait-aware proc-macro attributes such as impl-by-delegation.
- [dirmod](https://github.com/SOF3/dirmod), a Rust macro to smartly detect modules to include
- [rwlock-promise](https://github.com/SOF3/rwlock-promise), a JavaScript library that implements mutually-exclusive and shared-exclusive locks with a Promise API
- [thisrc](https://github.com/SOF3/php-ext-thisrc), a PHP extension that observes the refcount of the `$this` object without inducing side effects
- [xylem](https://github.com/SOF3/xylem), a Rust framework for statetul type conversion (a post-deserialize processing stage).

I have also created numerous tiny macros and libraries in Rust,
but those generally have very ad-hoc purposes
and are not known to have any other users.
Examples include [serde-iter](https://github.com/SOF3/serde-iter),
[count-write](https://github.com/SOF3/count-write),
[xias](https://github.com/SOF3/xias),
[qualify-derive](https://github.com/SOF3/qualify-derive), etc.

#### Programming language analysis
- [enclavlow](https://github.com/SOF3/enclavlow), my final year project that performs Java flow analysis to verify SGX data security.

#### Cloud native
- [Kelemetry](https://github.com/kubewharf/kelemetry), an observability tool to provide global control plane tracing for Kubernetes.
- [KubeAdmiral](https://github.com/kubewharf/kubeadmiral), a multi-cluster orchestrator and scheduler for Kubernetes.
- [KubeZoo](https://github.com/kubewharf/kubezoo), a lightweight multi-tenancy solution for Kubernetes.

#### Game development
- [PocketMine-MP](https://github.com/pmmp/PocketMine-MP), a reverse-engineered Minecraft server software.
  - PocketMine-MP has a huge ecosystem of plugins, and most of my work in earlier years were related to developing tools and cohesion of the ecosystem,
    such as dependency management, build tools and common-dependency APIs.
  - PocketMine-MP is an ancient project started in 2012. Some of my contributions include introducing modern tools and paradigms to the project.
  - :hourglass_flowing_sand: [libglocal-idea-plugin](libglocal-idea-plugin), an intellij plugin for editing [libglocal](https://github.com/SOF3/libglocal) language files
- :hourglass_flowing_sand: [Traffloat](https://github.com/traffloat/traffloat), a 3D web game written in Rust.
- :hourglass_flowing_sand: [dynec](https://github.com/SOF3/dynec), an ECS library that focuses on type safety and optimized for specific scenarios.

#### Systems programming
- [include-flate](https://github.com/SOF3/include-flate), a Rust macro for attaching constants as deflated strings in the executable.
- [phar.rs](https://github.com/SOF3/phar.rs), a Rust library for the PHAR (PHp ARchive) format. Also includes a WASM app and a CLI command for phar manipulation.
- [signed-vimrc](https://github.com/SOF3/signed-vimrc), a vim plugin that loads PGP-signed .vimrc files in cwd
- :hourglass_flowing_sand: [pathetique](https://github.com/SOF3/pathetique), an object-oriented abstraction of OS paths in PHP

#### Robotics
I was a member of the [HKU Robocon Team](https://github.com/m2robocon).

#### Web development
- :hourglass_flowing_sand: [octorest](https://github.com/SOF3/octorest), generated Rust bindings for the GitHub API (can adapt to other OpenAPI implementations too)
- :hourglass_flowing_sand: [webcord](https://github.com/SOF3/webcord), a webapp + discord bot that mirrors a discord chat

#### Android development
- [AndTransfer](https://github.com/SOF3/AndTransfer), a simple Android app that shares files to any [transfer.sh](https://transfer.sh) server.
- [Mentamatics](https://github.com/SOF3/Mentamatics), an app to train mental arithmetic calculation
- [MySQLClientCompact](https://github.com/SOF3/MySQLClientCompact), a small MySQL browser.

#### Discord bots
The Discord bots I write follow minimalistic approach
and rarely have sophisticated framework.

- [bthint](https://github.com/SOF3/bthint), a bot that tries to extract syntactically correct code from chat messages
- [boredphoton](https://github.com/pmmp/boredphoton), a minimalistic bot for alerting spam raids
- [orbs.bot](https://github.com/SOF3/orbs.bot), a fan project that reverse engineers the API of the webgame orbs.it and mirrors live games
- :hourglass_flowing_sand: [blob-mirror](https://SOF3/blob-mirror), a bot mirroring GitHub markdown files to Discord.
- :hourglass_flowing_sand: [webcord](https://github.com/SOF3/webcord), a webapp + discord bot that mirrors a discord chat

### Other accounts
- [StackOverflow](https://stackoverflow.com/users/3990767/sofe)/[StackExchange](https://stackexchange.com/users/4958971/sofe)
- [Keybase](https://keybase.io/sofe)
