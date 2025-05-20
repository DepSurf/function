# Function: <code>put_compat_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263880)
Location: fs/compat.c:212
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_statfs
  - fs/compat.c:C_SYSC_fstatfs
```
**Symbols:**

```
ffffffff81263880-ffffffff812639ff: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128fa10)
Location: fs/compat.c:212
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_fstatfs
  - fs/compat.c:C_SYSC_statfs
```
**Symbols:**

```
ffffffff8128fa10-ffffffff8128fb92: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a49f0)
Location: fs/compat.c:198
Inline: False
Direct callers:
  - fs/compat.c:C_SYSC_fstatfs
  - fs/compat.c:C_SYSC_statfs
```
**Symbols:**

```
ffffffff812a49f0-ffffffff812a4b72: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a400)
Location: fs/statfs.c:247
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_fstatfs
  - fs/statfs.c:C_SYSC_statfs
```
**Symbols:**

```
ffffffff8128a400-ffffffff8128a503: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812acf40)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_fstatfs
  - fs/statfs.c:C_SYSC_statfs
```
**Symbols:**

```
ffffffff812acf40-ffffffff812ad043: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4a80)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff812d4a80-ffffffff812d4b7f: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812e9e50)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff812e9e50-ffffffff812e9f4f: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308850)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81308850-ffffffff8130894f: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131b8f0)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff8131b8f0-ffffffff8131b9ef: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813556c0)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff813556c0-ffffffff813557be: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81361fe0)
Location: fs/statfs.c:264
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81361fe0-ffffffff813620de: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81368ac0)
Location: fs/statfs.c:267
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81368ac0-ffffffff81368bbe: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b77c0)
Location: fs/statfs.c:267
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff813b77c0-ffffffff813b78be: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143cd00)
Location: fs/statfs.c:267
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff8143cd00-ffffffff8143ce31: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cb490)
Location: fs/statfs.c:267
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff814cb490-ffffffff814cb5c1: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff815016d0)
Location: fs/statfs.c:267
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff815016d0-ffffffff81501801: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536320)
Location: fs/statfs.c:267
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81536320-ffffffff81536451: put_compat_statfs (STB_LOCAL)
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
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3608)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffff8000103d3608-ffff8000103d375c: put_compat_statfs (STB_LOCAL)
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
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d5b20)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
c0000000004d5b20-c0000000004d5c60: put_compat_statfs (STB_LOCAL)
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
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81313ed0)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81313ed0-ffffffff81313fcf: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304ae0)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81304ae0-ffffffff81304bdf: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81311cc0)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81311cc0-ffffffff81311dbf: put_compat_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs *ubuf, struct kstatfs *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323500)
Location: fs/statfs.c:262
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_compat_sys_statfs
```
**Symbols:**

```
ffffffff81323500-ffffffff813235ff: put_compat_statfs (STB_LOCAL)
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
