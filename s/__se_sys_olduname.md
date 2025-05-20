# Function: <code>__se_sys_olduname</code>

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
In kernel/sys.c (ffffffff810a5c1f)
Location: kernel/sys.c:1294
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810ae91f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810b331f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810b990f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810c0d65)
Location: kernel/sys.c:1309
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810bbec5)
Location: kernel/sys.c:1310
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810bd765)
Location: kernel/sys.c:1327
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810cfe05)
Location: kernel/sys.c:1336
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810e8564)
Location: kernel/sys.c:1343
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff81109354)
Location: kernel/sys.c:1344
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff81115664)
Location: kernel/sys.c:1362
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff8111f054)
Location: kernel/sys.c:1362
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
</details>
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_olduname(long int name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015d9e0)
Location: kernel/sys.c:1295
Inline: False
```
**Symbols:**

```
c00000000015d9e0-c00000000015dbb8: __se_sys_olduname (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b3c7f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810a25af)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810b31df)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810bbbff)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
