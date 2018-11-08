![30 Seconds Of Elixir Code](./media/logo.png)

# 30 Seconds Of Elixir Code

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

> A curated collection of useful Elixir snippets that you can understand in 30 seconds or less.

**Note**: This project is inspired by [30 Seconds Of Code](https://github.com/30-seconds/30-seconds-of-code), but there's no affiliation of any kind with that project.

:sparkles: **Always work in progress** :sparkles:

## Table of Contents

### 📚 Array

<details>

  <summary>View contents</summary>

  * [`all_equal`](#all_equal)

</details>

---

## 📚 Array

### all_equal

Check if all the elements in an array are equal.

```elixir
def all_equal(arr), do: arr |> Enum.dedup() |> Enum.count() == 1
```

<details>

  <summary>Examples</summary>

  ```elixir
  all_equal([1, 2, 3, 4, 5, 6])  # false
  all_equal([1, 1, 1])           # true
  ```
</details>

<br>[⬆ Back to top](#table-of-contents)

----------------------------

This project was developed by [dreamingechoes](https://github.com/dreamingechoes).
It adheres to its [code of conduct](https://github.com/dreamingechoes/base/blob/master/files/CODE_OF_CONDUCT.md) and
[contributing guidelines](https://github.com/dreamingechoes/base/blob/master/files/CONTRIBUTING.md), and uses an equivalent [license](https://github.com/dreamingechoes/base/blob/master/files/LICENSE).
