# Function: <code>__se_compat_sys_preadv2</code>

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
In fs/read_write.c (ffffffff81298e62)
Location: fs/read_write.c:1274
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff812adce2)
Location: fs/read_write.c:1271
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff812ca979)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff812dc399)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff81312f09)
Location: fs/read_write.c:1380
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff8131e6a5)
Location: fs/read_write.c:1135
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff813240e5)
Location: fs/read_write.c:1133
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff81371d05)
Location: fs/read_write.c:1124
Inline: True
Inline callers:
  - fs/read_write.c:__x64_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff813efce5)
Location: fs/read_write.c:1135
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff81478325)
Location: fs/read_write.c:1128
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff814ac8b5)
Location: fs/read_write.c:1127
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff814de325)
Location: fs/read_write.c:1169
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffff800010381d70)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_compat_sys_preadv2
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_compat_sys_preadv2(long int fd, long int vec, long int vlen, long int pos_low, long int pos_high, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004782b0)
Location: fs/read_write.c:1296
Inline: False
```
**Symbols:**

```
c0000000004782b0-c0000000004782f0: __se_compat_sys_preadv2 (STB_GLOBAL)
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
In fs/read_write.c (ffffffff812d4979)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff812c55f9)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff812d2789)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
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
In fs/read_write.c (ffffffff812e35e9)
Location: fs/read_write.c:1296
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_preadv2
  - fs/read_write.c:__ia32_compat_sys_preadv2
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
