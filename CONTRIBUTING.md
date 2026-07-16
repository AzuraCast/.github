# Contributing to AzuraCast

As a free and open-source software project, we eagerly welcome contributions from the community. There are many ways to
help contribute to AzuraCast's development, so you can make a difference without being a seasoned developer.

## Contributing Code Changes

AzuraCast is open-source software, and as part of this dedication to openness and transparency, we fully support
contributions from members of the community who are skilled in the languages that we use to build our applications.

A majority of our repositories come with an `.editorconfig` file in the root, which will set many standards for
indentation, punctuation and other style items for you automatically. You may need to enable EditorConfig support in
your IDE of choice.

If your IDE does not support EditorConfig, the most important standard to remember that we follow is the PHP Framework
Interoperability Group's [PER Coding Style](https://www.php-fig.org/per/coding-style/) recommendations.

Accessibility, security, and modern best practices are very important in AzuraCast's development. Any newly contributed
code can, and should, take advantage of the full suite of new features made available in PHP 8 and newer.

Instructions for developing with AzuraCast locally
are [available here](https://azuracast.com/docs/developers/getting-started/). If you have questions about the
guidelines above or about how to contribute to AzuraCast, please create a Github issue, join
our [Discord server.](https://www.azuracast.com/discord) Please note that support is offered on an 'as available' basis.

## Translating AzuraCast

Do you speak both English and another language? You can help us in a _big_ way by helping translate AzuraCast!

AzuraCast is used around the world, and we want our web application to be accessible to users who aren't familiar with
English, our primary language.

Thanks to the help of our friends at CrowdIn, translating the strings used in our application is easy!
Just [follow this invite link](https://crowdin.com/project/azuracast/invite) and create an account, and you can start
submitting translations. CrowdIn also provides suggested translations in case you are unsure of certain words or
phrases.

We do our best to incorporate translation changes as frequently as possible, but sometimes new updates are delayed. If
you have completed a significant translation project, please feel free to give us a gentle reminder by creating a Github
issue. Once the translations have been updated, we will close the issue to let you know.

## Testing New Platforms

Getting a project as large and complex as AzuraCast to work on many platforms is a huge effort, and is often far too
complex for a single-developer project such as this.

Thankfully, we've adopted support for Docker, a tool that allows us to create prebuilt images with all of our software
stack properly configured and arranged, which you can then run on just about any host that will run the latest version
of Docker. It's portable, it's cross-platform, and pulling down new updates are far easier than before; for these
reasons, we heavily emphasize using Docker over our older, Ubuntu-specific Ansible installation.

Although we use Docker in local development and on our testing and demonstration servers, sometimes a problem will occur
that stops a particular host from working with our application. If you're a user affected by such an issue, we encourage
you to advise us by creating a Github issue, especially if there is a known solution to the issue that we can apply.

## The "Do Nots" of Contributing

While we appreciate everyone who is eager to contribute to this project and help it succeed, we must ask that some forms
of interaction be avoided:

- Please **do not e-mail the project developer directly** with questions or issues specific to AzuraCast, unless you
  were specifically requested to do so as part of an ongoing issue. Contacting me directly prevents me from tracking all
  outstanding issues in one place, and harms the transparency that is essential to FOSS development.

  I do, however, accept e-mails in regards to paid contract work. 😀

- Please **do not create "this doesn't work" issues** that are just one sentence long and don't provide any insight into
  the scope of the issue, what changes might have triggered it, or what platform you're running on. At the very minimum,
  please fill out the template provided, as it gives us a lot of information to debug and provide you with support.

- Please **refer to existing Github issues** if you are curious about the status of outstanding bug reports or new
  enhancement requests. Always remember that this is a volunteer project primarily built and maintained by a single
  developer, and manage your expectations accordingly.

## Our Policy on Generative AI

AzuraCast is proud to be a software suite that is built and maintained by passionate humans. We consider the human element of code (and the humans we impact with our work) to be absolutely essential to why we invest so much time and energy into this project.

This does not mean that we are completely opposed to (or ignorant to) the benefits offered by today's generative AI tools and coding assistants. Even for seasoned professionals, these tools can make quick work of otherwise mundane tasks, and their role as assistive technology is also substantial. We do not want to fully reject the use of these technologies, but we have established guidelines to help avoid the most common faults and pain points we experience.

- **100% Human-Reviewed Code**: Whether your code is hand-written or generated by an AI assistant, you are expected to fully review and sign off on every line contributed to our codebases. This means ensuring that your code passes our test suites, matches our formatting expectations and follows best practices. We consider code contributed by your account to belong to you, not any AI agent, and we communicate accordingly. We also expect that any contributor will be familiar enough with our application structure and the technologies we use to be capable of signing off on their contributions.

- **No "Vibe-Coding"**: Do not use AI assistants as a substitute for the fundamental roles of software design or development. For example, if you are not familiar with the technologies that power AzuraCast and its related apps, do not simply tell an AI agent to build out a feature that you wish existed. We review any incoming issues and pull requests, and if it is highly evident to us that an entire component or feature was "vibe-coded", we may reject it in its entirety. 

- **AI as Assistive Technology**: There are scenarios where AI agents can greatly assist users who have specific challenges. Some examples include users who don't speak English as their primary language using automated translation tools to get help, or visually impaired users using AI agents to help scan and understand the codebase quickly. Accessibility is a first-class priority of ours, and we support these use cases. We just ask that you let us know if you are using AI in an assistive capacity so that we can help you better; we are happy to review your contributed code ourselves and apply any necessary fixes.

If you have questions or are unsure of whether your use of generative AI technology falls within these guidelines, feel free to reach out and ask a member of our team.

## Support AzuraCast

AzuraCast welcomes support from the community in the form of financial support as well. By supporting us financially, you help us keep living essentials paid for and allow us to work harder on contributing to the open-source ecosystem.

Visit the [AzuraCast Donations Page](https://donate.azuracast.com/) for up-to-date information on how to support AzuraCast financially.
