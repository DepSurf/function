# Function: <code>__do_sys_msync</code>

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
In mm/msync.c (ffffffff8123befa)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
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
In mm/msync.c (ffffffff8125031a)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
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
In mm/msync.c (ffffffff81262630)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
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
In mm/msync.c (ffffffff81270de0)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff812a1490)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff812a1490-ffffffff812a1679: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff812acca0)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff812acca0-ffffffff812acf22: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff812b1f80)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff812b1f80-ffffffff812b2211: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff812f3b70)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff812f3b70-ffffffff812f3e09: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff81357990)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff81357990-ffffffff81357c76: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff813d2140)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff813d2140-ffffffff813d23e8: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff81406cf0)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff81406cf0-ffffffff81406fad: __do_sys_msync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_msync(long unsigned int start, size_t len, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/msync.c (ffffffff814333a0)
Location: mm/msync.c:32
Inline: False
Direct callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
**Symbols:**

```
ffffffff814333a0-ffffffff8143365d: __do_sys_msync (STB_LOCAL)
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
In mm/msync.c (ffff800010306e38)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
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
In mm/msync.c (c0524a60)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
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
In mm/msync.c (c0000000003d4ed0)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
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
In mm/msync.c (ffffffe00021246e)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
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
In mm/msync.c (ffffffff81269430)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
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
In mm/msync.c (ffffffff8125b720)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
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
In mm/msync.c (ffffffff812671d0)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
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
In mm/msync.c (ffffffff81276b70)
Location: mm/msync.c:32
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
