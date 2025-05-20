# Function: <code>io_uring_setup</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813315a0)
Location: fs/io_uring.c:3406
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff813315a0-ffffffff81331666: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813451e0)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff813451e0-ffffffff813452a6: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81385b60)
Location: fs/io_uring.c:8276
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff81385b60-ffffffff81385bf6: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396e30)
Location: fs/io_uring.c:9834
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff81396e30-ffffffff81396ec6: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a0a0)
Location: fs/io_uring.c:9756
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff8139a0a0-ffffffff8139a136: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e91b0)
Location: fs/io_uring.c:10429
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff813e91b0-ffffffff813e9246: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:12118
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff816d67e0-ffffffff816d688a: io_uring_setup (STB_LOCAL)
ffffffff81e928ab-ffffffff81e928c0: io_uring_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178cfb0)
Location: io_uring/io_uring.c:3713
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff8178cfb0-ffffffff8178d05f: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce0f0)
Location: io_uring/io_uring.c:4024
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff817ce0f0-ffffffff817ce19f: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81816c70)
Location: io_uring/io_uring.c:4033
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff81816c70-ffffffff81816d1f: io_uring_setup (STB_LOCAL)
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
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010403ee8)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__arm64_sys_io_uring_setup
```
**Symbols:**

```
ffff800010403ee8-ffff8000104040d8: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d6a8c)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_setup
```
**Symbols:**

```
c05d6a8c-c05d6be0: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050ff80)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_setup
```
**Symbols:**

```
c00000000050ff80-c000000000510078: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002b0c4a)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_setup
```
**Symbols:**

```
ffffffe0002b0c4a-ffffffe0002b0cdc: io_uring_setup (STB_LOCAL)
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
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133d7c0)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff8133d7c0-ffffffff8133d886: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e480)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff8132e480-ffffffff8132e546: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133b290)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff8133b290-ffffffff8133b356: io_uring_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134e440)
Location: fs/io_uring.c:3976
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff8134e440-ffffffff8134e506: io_uring_setup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
