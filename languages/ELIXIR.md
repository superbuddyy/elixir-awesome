## A

[**Azimutt**](https://github.com/azimuttapp/azimutt) - Powerful database explorer, open-source and privacy-friendly

## B

[**Bandit**](https://github.com/mtrudel/bandit) - a pure Elixir web server supporting HTTP1, HTTP2 and WebSockets connections.

<br>

[**broadway**](https://github.com/dashbitco/broadway) Concurrent and multi-stage data ingestion and data processing with Elixir.

## C

[**cachex**](https://github.com/whitfin/cachex) A powerful caching library for Elixir with support for transactions, fallbacks and expirations.

<br>

[**credo**](https://github.com/rrrene/credo)  —  a static code analysis tool for the Elixir language with a focus on teaching and code consistency.

## D

[**distillery**](https://github.com/bitwalker/distillery)  —  a pure Elixir implementation of release packaging functionality for the Erlang VM (BEAM).
Every alchemist requires good tools, and one of the greatest tools in the alchemist’s disposal is the distillery. The purpose of the distillery is to take something and break it down to it’s component parts, reassembling it into something better, more powerful. That is exactly what this project does — it takes your Mix project and produces an Erlang/OTP release, a distilled form of your raw application’s components; a single package which can be deployed anywhere, independently of an Erlang/Elixir installation. No dependencies, no hassle.

This is a pure-Elixir, dependency-free implementation of release generation for Elixir projects. It is currently a standalone package, but may be integrated into Mix at some point in the future.

## E

[**Ecto**](https://github.com/elixir-ecto/ecto). A toolkit for data mapping and language integrated query.

Ecto is commonly used to interact with databases, such as PostgreSQL and MySQL via `Ecto.Adapters.SQL` (source code). Ecto is also commonly used to map data from any source into Elixir structs, whether they are backed by a database or not.

<br>

[**Elixir XDR**](https://github.com/kommitters/elixir_xdr) is an open data format, specified in [RFC 4506](http://tools.ietf.org/html/rfc4506.html). This library provides a way to decode and encode XDR data from Elixir. Extend with ease to other XDR types.

<br>

[**ExVCR**](https://github.com/parroty/exvcr). Record and replay HTTP interactions library for elixir. It's inspired by Ruby's VCR (https://github.com/vcr/vcr), and trying to provide similar functionalities.

Basics

- The following HTTP libraries can be applied.
    - <a href="https://github.com/cmullaparthi/ibrowse" target="_blank">ibrowse</a>-based libraries.
        - <a href="https://github.com/myfreeweb/httpotion" target="_blank">HTTPotion</a>
    - <a href="https://github.com/benoitc/hackney" target="_blank">hackney</a>-based libraries.
        - <a href="https://github.com/edgurgel/httpoison" target="_blank">HTTPoison</a>
        - support is very limited, and tested only with sync request of HTTPoison yet.
    - <a href="http://erlang.org/doc/man/httpc.html" target="_blank">httpc</a>-based libraries.
        - <a href="https://github.com/tim/erlang-oauth/" target="_blank">erlang-oauth</a>
        - <a href="https://github.com/Zatvobor/tirexs" target="_blank">tirexs</a>
        - support is very limited, and tested only with :httpc.request/1 and :httpc.request/4

- HTTP interactions are recorded as JSON file.
    - The JSON file can be recorded automatically (vcr_cassettes) or manually updated (custom_cassettes)

## F

[**Faker**](https://github.com/igas/faker) is a pure Elixir library for generating fake data.

<br>

[**Firezone**](https://github.com/firezone/firezone) is a remote access manager written in Elixir.
* Manage remote access through an intuitive web interface and CLI utility.
* Deploy on your own infrastructure to keep control of your network traffic.
* Built on WireGuard® to be stable, performant, and lightweight.

<br>

[**Floki**](https://github.com/philss/floki) is a simple HTML parser that enables search for nodes using CSS selectors.

Take this HTML as an example:

```html
<!doctype html>
<html>
<body>
  <section id="content">
    <p class="headline">Floki</p>
    <span class="headline">Enables search using CSS selectors</span>
    <a href="http://github.com/philss/floki">Github page</a>
    <span data-model="user">philss</span>
  </section>
  <a href="https://hex.pm/packages/floki">Hex package</a>
</body>
</html>
```

Here are some queries that you can perform (with return examples):

```elixir
Floki.find(html, "#content")
# => [{"section", [{"id", "content"}],
# =>  [{"p", [{"class", "headline"}], ["Floki"]},
# =>   {"a", [{"href", "http://github.com/philss/floki"}], ["Github page"]}]}]


Floki.find(html, "p.headline")
# => [{"p", [{"class", "headline"}], ["Floki"]}]

Floki.find(html, "p.headline")
|> Floki.raw_html
# => <p class="headline">Floki</p>


Floki.find(html, "a")
# => [{"a", [{"href", "http://github.com/philss/floki"}], ["Github page"]},
# =>  {"a", [{"href", "https://hex.pm/packages/floki"}], ["Hex package"]}]


Floki.find(html, "a[href^=https]")
# => [{"a", [{"href", "http://github.com/philss/floki"}], ["Github page"]},
# =>  {"a", [{"href", "https://hex.pm/packages/floki"}], ["Hex package"]}]


Floki.find(html, "#content a")
# => [{"a", [{"href", "http://github.com/philss/floki"}], ["Github page"]}]


Floki.find(html, "[data-model=user]")
# => [{"span", [{"data-model", "user"}], ["philss"]}]


Floki.find(html, ".headline, a")
# => [{"p", [{"class", "headline"}], ["Floki"]},
# =>  {"a", [{"href", "http://github.com/philss/floki"}], ["Github page"]},
# =>  {"a", [{"href", "https://hex.pm/packages/floki"}], ["Hex package"]}]
```

## G

[**guardian**](https://github.com/ueberauth/guardian)  —  an authentication framework for use with Elixir applications.
Guardian is based on similar ideas to Warden but is re-imagined for modern systems where Elixir manages the authentication requirements.

Guardian remains a functional system. It integrates with Plug, but can be used outside of it. If you’re implementing a TCP/UDP protocol directly, or want to utilize your authentication via channels, Guardian is your friend.
The core currency of authentication in Guardian is JSON Web Tokens (JWT). You can use the JWT to authenticate web endpoints, channels, and TCP sockets and it can contain any authenticated assertions that the issuer wants to include.

## H

[**httpoison** ](https://github.com/edgurgel/httpoison) —  yet another HTTP client for Elixir powered by hackney.

## K

[**kitto** ](https://github.com/kittoframework/kitto) —  a framework to help you create dashboards, written in Elixir/React.


## P

[**Phoenix**](http://www.phoenixframework.org/)  —  Productive. Reliable. Fast. A productive web framework that does not compromise speed and maintainability.

<br>

[**Plausible**](https://github.com/plausible/analytics)  -  Simple, open-source, lightweight (< 1 KB) and privacy-friendly web analytics alternative to Google Analytics.


## Q

[**Quantum**](https://github.com/quantum-elixir/quantum-core) - is a Cron-like job scheduler for Elixir.

## S

[**Stellar Base**](https://github.com/kommitters/stellar_base) is an Elixir library that provides a complete set of functions to read, write, hash, and sign XDR constructs used in [stellar-core](https://github.com/stellar/stellar-core).

<br>

[**Stellar SDK**](https://github.com/kommitters/stellar_sdk) enables the construction, signing and encoding of Stellar [transactions](https://developers.stellar.org/docs/glossary/transactions) and [operations](https://developers.stellar.org/docs/start/list-of-operations) in **Elixir**, as well as provides a client for interfacing with [Horizon](https://developers.stellar.org/api/introduction) server REST endpoints to retrieve ledger information, and to submit transactions.

This library is aimed at developers building Elixir applications that interact with the [**Stellar network**](https://www.stellar.org/).

<br>

[**Swoosh**](https://github.com/swoosh/swoosh) - Compose, deliver and test your emails easily in Elixir
Swoosh comes with many adapters, including SendGrid, Mandrill, Mailgun, Postmark and SMTP.

## T

[**timex** ](https://github.com/bitwalker/timex) —  a rich, comprehensive Date/Time library for Elixir projects, with full timezone support via the :tzdata package. If you need to manipulate dates, times, datetimes, timestamps, etc., then Timex is for you! It is very easy to use Timex types in place of default Erlang types, as well as Ecto types via the timex_ecto package.

Here’s a few simple examples:
```elixir
> use Timex
> Timex.today
~D[2016-02-29]

> datetime = Timex.now
#<DateTime(2016-02-29T12:30:30.120+00:00Z Etc/UTC)

> Timex.now("America/Chicago")
#<DateTime(2016-02-29T06:30:30.120-06:00 America/Chicago)

> Duration.now
#<Duration(P46Y6M24DT21H57M33.977711S)>

> {:ok, default_str} = Timex.format(datetime, "{ISO:Extended}")
{:ok, "2016-02-29T12:30:30.120+00:00"}

> {:ok, relative_str} = Timex.shift(datetime, minutes: -3) |> Timex.format("{relative}", :relative)
{:ok, "3 minutes ago"}

> strftime_str = Timex.format!(datetime, "%FT%T%:z", :strftime)
"2016-02-29T12:30:30+00:00"

> Timex.parse(default_str, "{ISO:Extended}")
{:ok, #<DateTime(2016-02-29T12:30:30.120+00:00 Etc/Utc)}

> Timex.parse!(strftime_str, "%FT%T%:z", :strftime)
#<DateTime(2016-02-29T12:30:30.120+00:00 Etc/Utc)
```
