<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<p align='center'>
  <img src='https://github.com/tunebond/moon.link/blob/make/view/moon.svg?raw=true' height='192'>
</p>

<h3 align='center'>moon.link</h3>
<p align='center'>
  Base Link Standard Library Specification
</p>

<br/>
<br/>
<br/>

## Welcome

The [`wolf.link`](https://github.com/tunebond/wolf.link) library is one possible implementation of this interface. The goal of separating `moon.link` from `wolf.link` is so that one could theoretically develop an optimal version of the implementation in parallel to a basic implementation, then swap them out, without interferring with the main library interface. This `moon.link` library is basically the specification for the standard library. It could also be used in other programming languages as it doesn't have any implementation.

## Outline

The goal with the moon project is to define the properties and functions of a basic programming environment, without defining the implementation. This way a person making a programming language could just look at the "spec" of all the things needed to implement, and start implementing that. The wolf project then is one possible implementation of this spec.

The project is divided into 3 main code folders:

- `code/form`: These are the form masks, the form interfaces so to speak.
- `code/suit`: These are the suit masks, the traits so to speak.
- `code/task`: These are generic top-level task/function interfaces.

These can be imported and used in a project, rather than importing wolf, as the base types.

## Relationships

|                                                                   specification                                                                    |                                                                   implementation                                                                   | description                                                                                                                        |
| :------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------- |
|                                                [`moon.link`](https://github.com/tunebond/moon.link)                                                |                                                [`wolf.link`](https://github.com/tunebond/wolf.link)                                                | **Standard Library**                                                                                                               |
| <a href="https://github.com/tunebond/moon.link"><img src='https://github.com/tunebond/moon.link/blob/make/view/moon.svg?raw=true' height='64'></a> | <a href="https://github.com/tunebond/wolf.link"><img src='https://github.com/tunebond/wolf.link/blob/make/view/view.svg?raw=true' height='64'></a> | These are the lowest-level datatypes and standards for abstracting away architectures in a basic programming language environment. |
|                                                [`tree.link`](https://github.com/tunebond/tree.link)                                                |                                                [`crow.link`](https://github.com/tunebond/crow.link)                                                | **Framework**                                                                                                                      |
| <a href="https://github.com/tunebond/tree.link"><img src='https://github.com/tunebond/tree.link/blob/make/view/view.svg?raw=true' height='64'></a> | <a href="https://github.com/tunebond/crow.link"><img src='https://github.com/tunebond/crow.link/blob/make/view/view.svg?raw=true' height='64'></a> | These are high-level framework components, which is an opinionated abstraction for common web app development paradigms.           |

## License

Copyright 2022-2023 <a href='https://tune.bond'>TuneBond</a>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## TuneBond

This is being developed by the folks at [TuneBond](https://tune.bond), a California-based project for helping humanity master information and computation. TuneBond started off in the winter of 2008 as a spark of an idea, to forming a company 10 years later in the winter of 2018, to a moon of a project just beginning its development phases. It is entirely bootstrapped by working full time and running [Etsy](https://etsy.com/shop/mountbuild) and [Amazon](https://www.amazon.com/s?rh=p_27%3AMount+Build) shops. Also find us on [Facebook](https://www.facebook.com/tunebond), [Twitter](https://twitter.com/tunebond), and [LinkedIn](https://www.linkedin.com/company/tunebond). Check out our other GitHub projects as well!
