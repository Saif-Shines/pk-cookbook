# Welcome to the Portkey Cookbook

This is a collection of guides and examples for using Portkey, including [quickstart](./quickstarts/) to add multimodal AI gateway and Observability capabilities, while [How To&#39;s](./howtos/) teaches you techniques that help you solve LLM challenges in production.

## Get started with Portkey

Portkey API lets you get an [open-source multimodal AI gateway](https://github.com/Portkey-AI/gateway) and incorporate observability for your LLM apps.

1. Go to [Portkey app](https://portkey.ai/) and Signup/Login.
2. Get an Portkey API key.
3. [Make your first request](./quickstarts/first-request.md)

## Official SDKs

Get the official [Portkey SDKs](https://portkey.ai/docs/api-reference/portkey-sdk-client#install-the-portkey-sdk) (Python or NodeJS).

## Get help

Join the [LLMs in Prod community](https://www.portkey.ai/community)

## Contributing

Contributions are welcome. See [contributing](./CONTRIBUTING.md) to learn more.

Thank you for developing with the Gemini API! We’re excited to see what you create.

### FAQ

<details>

<summary>What is the philosophy behind the kebab case?</summary>

If the github repository is threaded like a place for good resources, then it's like a good book that users will use for bookmarking or read through URLs. The `kebab-casing` does not cause any issues for URLs representation, and is very intuitive just like a a piece of blog or tutorial.

</details>

<details>

<summary>Why terms: quickstarts and howtos ? </summary>

The usage of terms like `reliability` or `managing-prompts` come-off as value driven to readers, but they

- limited in the list of articles they hold
- need to be changed, when product or messaging changes

Another option, the usage of terms like `ai-gateway`, `observability`, `product`:

- These are chosen to adhere to how documentation is structred
- Documentation overhaul is very rare. Hence usually someone who is comfortable with docs will find this intuitive.

In the current case:

- the terms `quickstarts`, `howto`, `examples` are the part of learning journey.
- they are not closely-knit with `use-cases`, `product features` or `value` that may change in the future.
- they are extensible - quickstarts, or howtos maybe increasing or can be further sub-foldered

</details>

<details>

<summary> What is `examples` ? </summary>

The `examples` folder:

- allows makes it open ended to add any topic to it.
- when have flexibility to wait untile we find patterns, we can create a new category or move to `quickstarts` or `howto` or something new.

</details>

<details>

<summary> What is the philosophy with `README.md` file? </summary>

- When someone discovers a page on a website the messaging of value and what they can do with it takes precedence.
- When someone discovers github page, makes sure they get what it is in shortest realest possible and take them to sign up or set up. This will have them get involved real quick.

</details>

<details>

<summary> What about index of contents? </summary>

An index of contents can be treated optional, if we expect as fewer and non-frequent changes to the filenames or titles of the existing articles on the repo.

For example, consider "set up fallbacks form openai to azure-openai" or "prevent unncessary llm requests" articles. They go into `howtos` or `quickstarts` or `examples` in terms of folders. But with an index on readme, we can take the flexiblity of introducing a table, list, tags and put them into desired labels such as `end to end apps` or `demo` or `ai-gateway` or `reliablity` - since we can always update the README without impacting the URLs or broken links.

</details>

<details>

<summary> Why put md and ipynb files in same directories? </summary>

Well the altenative is have Python and NodeJS directories. The assumption with which an reader would be discovering

</details>
