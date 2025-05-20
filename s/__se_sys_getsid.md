# Function: <code>__se_sys_getsid</code>

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
In kernel/sys.c (ffffffff810a3bc5)
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
In kernel/sys.c (ffffffff810ac995)
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
In kernel/sys.c (ffffffff810b1f55)
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
In kernel/sys.c (ffffffff810b8625)
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
In kernel/sys.c (ffffffff810bffc5)
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
In kernel/sys.c (ffffffff810bb1e5)
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
In kernel/sys.c (ffffffff810bcb25)
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
In kernel/sys.c (ffffffff810d12f5)
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
In kernel/sys.c (ffffffff810e8075)
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
In kernel/sys.c (ffffffff81108de5)
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
In kernel/sys.c (ffffffff811150f5)
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
In kernel/sys.c (ffffffff8111eae5)
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
In kernel/sys.c (ffff800010114440)
Location: kernel/sys.c:1119
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_getsid(long int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036d130)
Location: kernel/sys.c:1119
Inline: False
```
**Symbols:**

```
c036d130-c036d1a4: __se_sys_getsid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_getsid(long int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015ca00)
Location: kernel/sys.c:1119
Inline: False
```
**Symbols:**

```
c00000000015ca00-c00000000015caa8: __se_sys_getsid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_getsid(long int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d3ea4)
Location: kernel/sys.c:1119
Inline: False
```
**Symbols:**

```
ffffffe0000d3ea4-ffffffe0000d3f06: __se_sys_getsid (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b2995)
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
In kernel/sys.c (ffffffff810a28c5)
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
In kernel/sys.c (ffffffff810b1ef5)
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
In kernel/sys.c (ffffffff810bbf15)
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
<b>Arch</b>
<ul>
</ul>
