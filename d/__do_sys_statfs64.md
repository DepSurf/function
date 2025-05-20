# Function: <code>__do_sys_statfs64</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d5180)
Location: fs/statfs.c:185
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff812d5180-ffffffff812d51e8: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea550)
Location: fs/statfs.c:185
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff812ea550-ffffffff812ea5b8: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308fc0)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81308fc0-ffffffff8130902a: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131c030)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff8131c030-ffffffff8131c09a: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81355d40)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81355d40-ffffffff81355da8: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81362680)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81362680-ffffffff813626e8: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81369120)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81369120-ffffffff81369188: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b7e20)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff813b7e20-ffffffff813b7e88: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d620)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff8143d620-ffffffff8143d6ab: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cbea0)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff814cbea0-ffffffff814cbf2b: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff815020e0)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff815020e0-ffffffff8150216b: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536d30)
Location: fs/statfs.c:201
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81536d30-ffffffff81536dbb: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d39d0)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__arm64_sys_statfs64
```
**Symbols:**

```
ffff8000103d39d0-ffff8000103d3a44: __do_sys_statfs64 (STB_LOCAL)
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
In fs/statfs.c (c05adfa0)
Location: fs/statfs.c:199
Inline: True
Inline callers:
  - fs/statfs.c:__se_sys_statfs64
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6400)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_statfs64
```
**Symbols:**

```
c0000000004d6400-c0000000004d64ac: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e32c)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_statfs64
```
**Symbols:**

```
ffffffe00028e32c-ffffffe00028e374: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81314610)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81314610-ffffffff8131467a: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81305220)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81305220-ffffffff8130528a: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81312400)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81312400-ffffffff8131246a: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_statfs64(const char *pathname, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323c40)
Location: fs/statfs.c:199
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_statfs64
  - fs/statfs.c:__x64_sys_statfs64
```
**Symbols:**

```
ffffffff81323c40-ffffffff81323caa: __do_sys_statfs64 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
