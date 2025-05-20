# Function: <code>user_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81241b00)
Location: fs/statfs.c:77
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_statfs
  - fs/statfs.c:SYSC_statfs64
  - fs/compat.c:C_SYSC_statfs
  - fs/compat.c:C_SYSC_statfs64
```
**Symbols:**

```
ffffffff81241b00-ffffffff81241b9d: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81269e50)
Location: fs/statfs.c:77
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_statfs64
  - fs/statfs.c:SYSC_statfs
  - fs/compat.c:C_SYSC_statfs64
  - fs/compat.c:C_SYSC_statfs
```
**Symbols:**

```
ffffffff81269e50-ffffffff81269eed: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127ce00)
Location: fs/statfs.c:77
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_statfs64
  - fs/statfs.c:SYSC_statfs
  - fs/compat.c:C_SYSC_statfs64
  - fs/compat.c:C_SYSC_statfs
```
**Symbols:**

```
ffffffff8127ce00-ffffffff8127ce9d: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a6e0)
Location: fs/statfs.c:80
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_statfs64
  - fs/statfs.c:C_SYSC_statfs
  - fs/statfs.c:SYSC_statfs64
  - fs/statfs.c:SYSC_statfs
```
**Symbols:**

```
ffffffff8128a6e0-ffffffff8128a780: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad400)
Location: fs/statfs.c:81
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_statfs64
  - fs/statfs.c:C_SYSC_statfs
  - fs/statfs.c:SYSC_statfs64
  - fs/statfs.c:SYSC_statfs
```
**Symbols:**

```
ffffffff812ad400-ffffffff812ad4a0: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d5040)
Location: fs/statfs.c:81
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff812d5040-ffffffff812d50e0: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea410)
Location: fs/statfs.c:81
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff812ea410-ffffffff812ea4b0: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308e70)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81308e70-ffffffff81308f14: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131bee0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff8131bee0-ffffffff8131bf84: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81355be0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81355be0-ffffffff81355ca0: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81362520)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81362520-ffffffff813625e0: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81368fc0)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81368fc0-ffffffff81369080: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b7cc0)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff813b7cc0-ffffffff813b7d80: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d480)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff8143d480-ffffffff8143d55b: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cbcc0)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff814cbcc0-ffffffff814cbd9b: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501f00)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81501f00-ffffffff81501fdb: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536b50)
Location: fs/statfs.c:97
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81536b50-ffffffff81536c2b: user_statfs (STB_GLOBAL)
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
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3878)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffff8000103d3878-ffff8000103d3934: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05adde0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_statfs64
  - fs/statfs.c:__se_sys_statfs
```
**Symbols:**

```
c05adde0-c05ade98: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6270)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
c0000000004d6270-c0000000004d635c: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e26a)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffe00028e26a-ffffffe00028e2f0: user_statfs (STB_GLOBAL)
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
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813144c0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff813144c0-ffffffff81314564: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813050d0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff813050d0-ffffffff81305174: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813122b0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff813122b0-ffffffff81312354: user_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int user_statfs(const char *pathname, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323af0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_statfs64
  - fs/statfs.c:__do_compat_sys_statfs
  - fs/statfs.c:__do_sys_statfs64
  - fs/statfs.c:__do_sys_statfs
```
**Symbols:**

```
ffffffff81323af0-ffffffff81323b94: user_statfs (STB_GLOBAL)
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
