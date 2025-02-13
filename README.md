https://rainbowbeast.substack.com/p/ddb9339f-d94d-4739-bca6-8171b5e2dcff

1. Fork this repository within GitHub:
    1. Navigate to [ethereum/ERCs](https://github.com/ethereum/ERCs).
    1. Find the "Fork" button in the upper right side of the screen and click it.
    1. Proceed with repository creation.

2. Clone your fork locally:
    1. `git clone https://github.com/{user}/ercs`

3. Enter the newly created `ercs` folder:
    1. `cd ercs`

4. Add your fork of the EIPs repository as a remote:
    1. `git remote add eips https://github.com/{user}/eips`

5. Fetch that remote to download your branches:
    1. `git fetch eips`

6. Now checkout the branch related to your original PR:
    1. `git checkout {branch}`

7. Rebase your branch against the ERCs repo:
    1. `git rebase master`
    2. Please note, you do not need to update any references of EIP to ERC; particularly in the relative links. Even though `[ERC-X](./eip-x.md)` doesn't correctly render in this repository, we're currently building the full `eips.ethereum.org` still in the `ethereum/eips` repository. So until we resolve this in #1, we will continue using this relative linking format.

8. Push your branch to your ERCs fork:
    1. `git push -u origin {branch}`

9. Now you can recreate your pull request:
    1. Navigate to https://github.com/ethereum/ERCs/compare
    3. Select your newly created fork and branch
    4. open a new PR to this repo.

Additional notes:

- Do NOT link to ERCs using their filename. Link to ERCs using `[ERC-XXXX](./eip-XXXX.md)`.

_Originally posted by @lightclient in https://github.com/ethereum/ERCs/issues/8_

_Originally posted by @GloWE3 in https://github.com/GloWE3/Rainbowbeast-Webkit/issues/1_ https://rsdvops.link.    https://gravatar.com/rainbowbeast5
RainbowScientist Playground Organization✨🌈
🙋‍♀️ Welcome to the #🌈✨RainbowScientist Playground Organization✨🌈

✨ Our mission is to showcase and demonstrate the best that GitHub has to offer. We focus on creating repositories that highlight various features and best practices for effective code management 👨🏽‍💼 and collaboration 🫂.

🍿 Featured Repository

The Demo Repository is a collection of projects and code samples available on GitHub under the 🌈✨RainbowScientist Playground✨🌈 organization. It includes various repositories such as:

🦄 Implementations of nodes for the Polygon zkEVM Network
🔷 Ethereum wallet applications
⛓️‍💥 Blockchain-related code
For more details, you can visit the 🌈✨RainbowScientist Playground Organization✨🌈 on GitHub.

Repository Contents

This repository demonstrates GitHub's capabilities with minimal noise. It includes:

An index.html file crucial for rendering a webpage
2️⃣ GitHub Actions workflows
🎼 CSS stylesheet dependency
👩‍💻 Contributing

If you're eager to contribute, we're open to everyone's input. Here’s how you can get started:

🔃 Fork the repository
🌿 Create a new branch for your feature or bug fix
📝 Submit a pull request with a clear description of your changes
🪪 License

This organization and its repositories are licensed under CC 4️⃣⛓️‍💥

💡 Getting Started

Here are some ideas to get you started:

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of Markdown.
