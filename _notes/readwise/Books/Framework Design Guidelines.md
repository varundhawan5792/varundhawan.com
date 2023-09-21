# Framework Design Guidelines

![rw-book-cover](https://m.media-amazon.com/images/I/51BB0uuIoHL._SY160.jpg)

## Metadata
- Author: [[Krzysztof Cwalina, Brad Abrams]]
- Full Title: Framework Design Guidelines
- Category: #books

## Highlights
- If you have any second thoughts about the complexity of a design, it is almost always much better to cut the feature from the current release and spend more time to get the design right for the next release. ([Location 599](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=599))
- If the design does not feel right, and you ship it anyway, you are likely to regret having done so. ([Location 601](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=601))
- The best framework designs are done either by people whose explicit responsibility is framework design, or by people who can put the framework designer’s hat on at the right time in the development process. ([Location 625](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=625))
- Design is all about making trade-offs, and to make the right decisions, you need to understand the options, their benefits, and their drawbacks. ([Location 631](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=631))
- Most successful frameworks borrow from and build on top of existing proven designs. ([Location 636](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=636))
- “Simple things should be simple and complex things should be possible.” ([Location 687](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=687))
- When designing a framework, concentrate on the important 20 percent of scenarios and APIs. ([Location 689](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=689))
- It is easy to design for users who are like you, and very difficult to design for somebody unlike you. ([Location 701](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=701))
- The main drawback3 is that the multitude of frameworks makes it difficult for developers using one of the frameworks to transfer their knowledge to the next skill level or scenario ([Location 726](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=726))
- The goal of a progressive framework is to scale through a broad range of developers, but not every possible developer. This clearly means that those developers who fall outside this target will need specialty APIs. ([Location 767](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=767))
- However, most development revolves around a small set of common scenarios that use a relatively small subset of the full framework. ([Location 789](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=789))
- We recommend that framework designers first write code that the users of the framework will have to write in main scenarios, and then design the object model to support these code samples. ([Location 792](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=792))
- Frameworks must be designed starting from a set of usage scenarios and code samples implementing these scenarios. ([Location 798](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=798))
- Framework designers often make the mistake of starting with the design of the object model (using various design methodologies) and then writing code samples ([Location 803](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=803))
- When designing a framework, you should start with producing a scenario-driven API specification ([Location 807](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=807))
- The specification should contain a scenario section listing the top five to ten scenarios for a given technology area and should show code samples that implement these scenarios. ([Location 810](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=810))
- it’s also incredibly difficult to step back and objectively assess whether some new capability that you’re particularly passionate about has utility in the real world. Using scenarios is the best way I know of to identify the need for and ideal usage of new capabilities. ([Location 839](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=839))
- It requires a unique combination of technical skill and customer understanding. ([Location 841](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=841))
- Although redesign is a costly practice, we found that it actually saves resources in the long run because the cost of fixing an unusable API without introducing changes that break existing code is enormous. ([Location 900](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=900))
- Low Barrier to Entry ([Location 904](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=904))
- Today, many developers expect to learn the basics of new frameworks very quickly. ([Location 904](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=904))
- Many developers want to experiment with an API to discover what it does and then adjust their code slowly to get their program to do what they really want. ([Location 911](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=911))
- Most developers, regardless of the language that they work in, learn by doing. ([Location 914](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=914))
- To be easy to experiment with, an API must do the following: ([Location 920](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=920))
- A framework that requires an extensive initialization or an instantiating of several types and then hooking them together is not easy to experiment with. ([Location 933](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=933))
- For example, APIs should throw exceptions that clearly describe what needs to be done to fix the problem. ([Location 944](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=944))
- DO provide good defaults for all properties and parameters ([Location 992](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=992))
- In simple scenarios, frameworks must be usable without the need for documentation. ([Location 1019](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=1019))
- Layered Architecture ([Location 1143](https://readwise.io/to_kindle?action=open&asin=B0017SWPNO&location=1143))
