# Function: <code>__do_sys_sigaltstack</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ca93)
Location: kernel/signal.c:3461
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4f93)
Location: kernel/signal.c:3786
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9c55)
Location: kernel/signal.c:4034
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0235)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7df5)
Location: kernel/signal.c:4060
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b30a5)
Location: kernel/signal.c:4097
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b46d5)
Location: kernel/signal.c:4119
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c68a5)
Location: kernel/signal.c:4211
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810de3c3)
Location: kernel/signal.c:4226
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fe873)
Location: kernel/signal.c:4228
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110a8e3)
Location: kernel/signal.c:4252
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114283)
Location: kernel/signal.c:4263
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010c2c8)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036a0fc)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152a84)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1c48)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_sigaltstack
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa5a5)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098f55)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9b05)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1f55)
Location: kernel/signal.c:4042
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
</details>
</li>
</ul>

## Differences
