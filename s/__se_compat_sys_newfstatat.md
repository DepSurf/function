# Function: <code>__se_compat_sys_newfstatat</code>

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
In fs/stat.c (ffffffff812a02e5)
Location: fs/stat.c:645
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff812b52c5)
Location: fs/stat.c:648
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff812d2075)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff812e3c05)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff8131ae05)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff81326495)
Location: fs/stat.c:665
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff8132c5a5)
Location: fs/stat.c:683
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff81379d15)
Location: fs/stat.c:701
Inline: True
Inline callers:
  - fs/stat.c:__x64_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff813f97b5)
Location: fs/stat.c:723
Inline: True
Inline callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff81482fd5)
Location: fs/stat.c:740
Inline: True
Inline callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff814b7bf5)
Location: fs/stat.c:753
Inline: True
Inline callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff814ea0f5)
Location: fs/stat.c:775
Inline: True
Inline callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffff80001038afd8)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__arm64_compat_sys_newfstatat
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dc1e5)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff812cce65)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff812d9ff5)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
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
In fs/stat.c (ffffffff812eaf05)
Location: fs/stat.c:650
Inline: True
Inline callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
</details>
</li>
</ul>

## Differences
