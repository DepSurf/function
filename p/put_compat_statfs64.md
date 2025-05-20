# Function: <code>put_compat_statfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263a60)
Location: fs/compat.c:268
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_statfs64
  - fs/compat.c:C_SYSC_fstatfs64
```
**Symbols:**

```
ffffffff81263a60-ffffffff81263b94: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128fc00)
Location: fs/compat.c:268
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_fstatfs64
  - fs/compat.c:C_SYSC_statfs64
```
**Symbols:**

```
ffffffff8128fc00-ffffffff8128fd29: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4be0)
Location: fs/compat.c:254
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_fstatfs64
  - fs/compat.c:C_SYSC_statfs64
```
**Symbols:**

```
ffffffff812a4be0-ffffffff812a4d66: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a510)
Location: fs/statfs.c:303
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_fstatfs64
  - fs/statfs.c:C_SYSC_statfs64
```
**Symbols:**

```
ffffffff8128a510-ffffffff8128a618: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad050)
Location: fs/statfs.c:304
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_fstatfs64
  - fs/statfs.c:C_SYSC_statfs64
```
**Symbols:**

```
ffffffff812ad050-ffffffff812ad158: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4b80)
Location: fs/statfs.c:304
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_statfs64
```
**Symbols:**

```
ffffffff812d4b80-ffffffff812d4c84: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812e9f50)
Location: fs/statfs.c:304
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff812e9f50-ffffffff812ea054: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308950)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81308950-ffffffff81308a5e: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131b9f0)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff8131b9f0-ffffffff8131bac5: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813557c0)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff813557c0-ffffffff8135589b: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813620e0)
Location: fs/statfs.c:320
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff813620e0-ffffffff813621bb: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81368bc0)
Location: fs/statfs.c:323
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81368bc0-ffffffff81368c9b: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b78c0)
Location: fs/statfs.c:323
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff813b78c0-ffffffff813b799b: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143ce40)
Location: fs/statfs.c:323
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff8143ce40-ffffffff8143cf33: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cb5e0)
Location: fs/statfs.c:323
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff814cb5e0-ffffffff814cb6d3: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501820)
Location: fs/statfs.c:323
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81501820-ffffffff81501913: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536470)
Location: fs/statfs.c:323
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81536470-ffffffff81536563: put_compat_statfs64 (STB_LOCAL)
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
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d34b8)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffff8000103d34b8-ffff8000103d3604: put_compat_statfs64 (STB_LOCAL)
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
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d5c60)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
c0000000004d5c60-c0000000004d5d70: put_compat_statfs64 (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81313fd0)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81313fd0-ffffffff813140a5: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304be0)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81304be0-ffffffff81304cb5: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81311dc0)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81311dc0-ffffffff81311e95: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323600)
Location: fs/statfs.c:318
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:kcompat_sys_statfs64
```
**Symbols:**

```
ffffffff81323600-ffffffff813236d5: put_compat_statfs64 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
