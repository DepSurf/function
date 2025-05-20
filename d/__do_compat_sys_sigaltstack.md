# Function: <code>__do_compat_sys_sigaltstack</code>

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
In kernel/signal.c (ffffffff8109cc95)
Location: kernel/signal.c:3526
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810a4f55)
Location: kernel/signal.c:3854
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810a9c15)
Location: kernel/signal.c:4102
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810b01f5)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810b7db5)
Location: kernel/signal.c:4128
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810b3065)
Location: kernel/signal.c:4165
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810b4695)
Location: kernel/signal.c:4187
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810c6865)
Location: kernel/signal.c:4275
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810de385)
Location: kernel/signal.c:4290
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810fe825)
Location: kernel/signal.c:4292
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff8110a895)
Location: kernel/signal.c:4316
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff81114235)
Location: kernel/signal.c:4327
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffff80001010c280)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_sigaltstack
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152a3c)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_sigaltstack
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/signal.c (ffffffff810aa565)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff81098f15)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810a9ac5)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
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
In kernel/signal.c (ffffffff810b1f15)
Location: kernel/signal.c:4110
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
</details>
</li>
</ul>

## Differences
