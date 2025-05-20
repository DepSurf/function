# Function: <code>__do_sys_unshare</code>

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
In kernel/fork.c (ffffffff8108e1b5)
Location: kernel/fork.c:2524
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff81096445)
Location: kernel/fork.c:2632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff8109a985)
Location: kernel/fork.c:2923
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810a0f45)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810a7da5)
Location: kernel/fork.c:3065
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810a3b25)
Location: kernel/fork.c:3045
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810a4775)
Location: kernel/fork.c:3083
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810b5f95)
Location: kernel/fork.c:3176
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810cc4b5)
Location: kernel/fork.c:3250
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810e9b85)
Location: kernel/fork.c:3286
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810f5785)
Location: kernel/fork.c:3522
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810feb35)
Location: kernel/fork.c:3512
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffff8000100f5920)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_unshare
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
In kernel/fork.c (c035409c)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_unshare
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
In kernel/fork.c (c00000000013bacc)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_unshare
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
In kernel/fork.c (ffffffe0000c1c5e)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_unshare
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
In kernel/fork.c (ffffffff8109a865)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810892a5)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff8109a815)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
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
In kernel/fork.c (ffffffff810a2495)
Location: kernel/fork.c:2940
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_unshare
  - kernel/fork.c:__x64_sys_unshare
```
</details>
</li>
</ul>

## Differences
