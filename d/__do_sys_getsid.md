# Function: <code>__do_sys_getsid</code>

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
In kernel/sys.c (ffffffff810a3bce)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810ac99e)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810b1f5f)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810b862f)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810bffcf)
Location: kernel/sys.c:1133
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810bb1f1)
Location: kernel/sys.c:1134
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810bcb31)
Location: kernel/sys.c:1151
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810d1301)
Location: kernel/sys.c:1160
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810e8080)
Location: kernel/sys.c:1167
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff81108df0)
Location: kernel/sys.c:1168
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff81115100)
Location: kernel/sys.c:1186
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff8111eaf0)
Location: kernel/sys.c:1186
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffff800010114444)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getsid
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
In kernel/sys.c (c036d144)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getsid
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
In kernel/sys.c (c00000000015ca24)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getsid
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
In kernel/sys.c (ffffffe0000d3ebe)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getsid
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
In kernel/sys.c (ffffffff810b299f)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810a28cf)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810b1eff)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
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
In kernel/sys.c (ffffffff810bbf21)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
```
</details>
</li>
</ul>

## Differences
