> [!NOTE]
> This section provides important context about the software installation process. Please ensure you have met all the prerequisites outlined in the previous chapter before proceeding. Failure to do so might lead to unexpected errors or an incomplete installation. Remember to consult the troubleshooting guide if you encounter any issues.

> [!IMPORTANT]
> Before running the main application, it is crucial to configure the environment variables correctly. These variables control access to external resources and define critical operational parameters. Incorrectly configured variables can result in the application failing to start or behaving erratically. Please refer to the `config.example.ini` file for the required settings and ensure you create a `.config.ini` file with your specific configurations.

> [!CAUTION]
> Modifying the core system files can lead to irreversible damage to your installation. Only proceed if you are absolutely sure of the changes you are making and have a reliable backup of your system. We strongly advise against directly editing these files unless explicitly instructed to do so by official documentation or support personnel. Any data loss or system instability resulting from unauthorized modifications is not the responsibility of the developers.

> [!Note]
> Stylua does not work by default in Termux because official binaries are not available for ARM64 or ARMv7 Android devices. If you'd like to use Stylua, you'll need
>
> 1.  Find or clone the Stylua source code from its GitHub repository.
> 2.  Install Rust using `pkg install rust` or `rustup`
> 3.  Build Stylua manually using `cargo build --release`
>     This process depends on your phone's architecture (ARM64-v8a or ARMv7). Once built successfully, you can integrate Stylua into your Neovim setup.
