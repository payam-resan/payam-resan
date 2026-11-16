<div align="center">

<a href="https://payam-resan.com">
  <img src="assets/logo.svg" width="72" height="72" alt="Payam Resan">
</a>

<h1>Payam Resan</h1>

<a href="README.md">فارسی</a> · <b>English</b>

</div>

---

Payam Resan is the SMS platform built by Moje Shahr. It has been delivering
messages for Iranian businesses since 2008: login codes, order updates,
appointment reminders.

## Where the examples went

The example repositories that used to live under this account have moved to the
[Moje Shahr](https://github.com/Mojeshahr) organization, so all the public code
sits in one place. No repository was renamed, only its owner:
`payam-resan/php-sms-webservice` is now `Mojeshahr/php-sms-webservice`.

Stars, forks, issues and commit history moved with each repository, and GitHub
redirects the old URLs automatically, so bookmarks and even a `git clone` of the
old address still work. To point an existing clone at the new URL explicitly:

```bash
git remote set-url origin https://github.com/Mojeshahr/php-sms-webservice.git
```

## Examples per language

Every language gets its own repository with one runnable file per API method,
ready to copy into your project. Each repository's README lists its prerequisites.

The API V3 examples include `SendTokenSingleConcatParam`: send a template with
semicolon-separated values in one `p` string, over either GET or POST.

<div align="center">

[![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)](https://github.com/Mojeshahr/php-sms-webservice)
[![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)](https://github.com/Mojeshahr/laravel-sms-webservice)
[![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)](https://github.com/Mojeshahr/nodejs-sms-webservice)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://github.com/Mojeshahr/typescript-sms-webservice)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://github.com/Mojeshahr/nextjs-sms-webservice)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://github.com/Mojeshahr/python-sms-webservice)
[![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)](https://github.com/Mojeshahr/go-sms-webservice)
[![Rust](https://img.shields.io/badge/Rust-CE422B?logo=rust&logoColor=white)](https://github.com/Mojeshahr/rust-sms-webservice)
[![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)](https://github.com/Mojeshahr/java-sms-webservice)
[![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)](https://github.com/Mojeshahr/csharp-sms-webservice)
[![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)](https://github.com/Mojeshahr/swift-sms-webservice)
[![Ruby](https://img.shields.io/badge/Ruby-CC342D?logo=ruby&logoColor=white)](https://github.com/Mojeshahr/ruby-sms-webservice)
[![VB.NET](https://img.shields.io/badge/VB.NET-5C2D91?logo=dotnet&logoColor=white)](https://github.com/Mojeshahr/vbnet-sms-webservice)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://github.com/Mojeshahr/kotlin-sms-webservice)
[![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)](https://github.com/Mojeshahr/dart-sms-webservice)
[![Delphi](https://img.shields.io/badge/Delphi-E62E2E?logo=delphi&logoColor=white)](https://github.com/Mojeshahr/delphi-sms-webservice)
[![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)](https://github.com/Mojeshahr/powershell-sms-webservice)
[![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?logo=microsoftsqlserver&logoColor=white)](https://github.com/Mojeshahr/tsql-sms-webservice)
[![curl](https://img.shields.io/badge/curl-073551?logo=curl&logoColor=white)](https://github.com/Mojeshahr/curl-sms-webservice)

</div>

The site documentation and examples use a single
[OpenAPI reference](https://github.com/Mojeshahr/sms-webservice-spec) as their contract.

There is also an [MCP server](https://github.com/Mojeshahr/mcp-sms-webservice),
for when you want an AI assistant to send the message and read the delivery
report itself, without you writing any code. A complete rewrite for API V4 is planned.

The browser-side examples are kept apart, in
[browser-sms-webservice](https://github.com/Mojeshahr/browser-sms-webservice),
written with `fetch`, `XMLHttpRequest`, jQuery and TypeScript. They are for
testing and learning, not for a real site: the account key is visible to every
visitor, and the browser refuses the request anyway over CORS. The
explanation you need is in that repository's README.

<div align="center">

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://github.com/Mojeshahr/browser-sms-webservice/tree/main/examples/v3-esm)
[![ES5](https://img.shields.io/badge/ES5-F7DF1E?logo=javascript&logoColor=black)](https://github.com/Mojeshahr/browser-sms-webservice/tree/main/examples/v3-es5)
[![jQuery](https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=white)](https://github.com/Mojeshahr/browser-sms-webservice/tree/main/examples/v3-jquery)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://github.com/Mojeshahr/browser-sms-webservice/tree/main/examples/v3-ts)

</div>

## Get started

| | |
|---|---|
| Web service documentation | [docs.payam-resan.com](https://docs.payam-resan.com) |
| Create an account and buy credit | [payam-resan.com](https://payam-resan.com) |
| The rest of the repositories | [github.com/Mojeshahr](https://github.com/Mojeshahr) |

<br>
<div align="center">
  <sub>
    <img src="assets/logo.svg" width="16" height="16" alt="" align="top">
    &nbsp;<b>Payam Resan SMS Panel - Moje Shahr</b>&nbsp;
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/mojeshahr-dark.svg">
      <img src="assets/mojeshahr-light.svg" width="16" height="16" alt="" align="top">
    </picture>
  </sub>
  <br>
  <sub>
    <a href="https://payam-resan.com">payam-resan.com</a>
    &nbsp;·&nbsp;
    <a href="https://mojeshahr.ir">mojeshahr.ir</a>
  </sub>
</div>
