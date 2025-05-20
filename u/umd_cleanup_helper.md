# Function: <code>umd_cleanup_helper</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void umd_cleanup_helper(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff810d5616)
Location: kernel/usermode_driver.c:150
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_cleanup
```
**Symbols:**

```
ffffffff810d53b0-ffffffff810d53e6: umd_cleanup_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void umd_cleanup_helper(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff810d72d6)
Location: kernel/usermode_driver.c:150
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_cleanup
```
**Symbols:**

```
ffffffff810d7070-ffffffff810d70a6: umd_cleanup_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void umd_cleanup_helper(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff810eab86)
Location: kernel/usermode_driver.c:150
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_cleanup
```
**Symbols:**

```
ffffffff810ea920-ffffffff810ea956: umd_cleanup_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void umd_cleanup_helper(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff8110597e)
Location: kernel/usermode_driver.c:150
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_cleanup
```
**Symbols:**

```
ffffffff811056d0-ffffffff8110570c: umd_cleanup_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void umd_cleanup_helper(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff8112b47e)
Location: kernel/usermode_driver.c:150
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_cleanup
```
**Symbols:**

```
ffffffff8112b1a0-ffffffff8112b1dc: umd_cleanup_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void umd_cleanup_helper(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff8113876e)
Location: kernel/usermode_driver.c:150
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_cleanup
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
```
**Symbols:**

```
ffffffff81138490-ffffffff811384cc: umd_cleanup_helper (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
