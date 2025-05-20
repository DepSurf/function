# Function: <code>do_statfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81241900)
Location: fs/statfs.c:148
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_statfs64
  - fs/statfs.c:SYSC_fstatfs64
```
**Symbols:**

```
ffffffff81241900-ffffffff812419c8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81269c40)
Location: fs/statfs.c:148
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_statfs64
```
**Symbols:**

```
ffffffff81269c40-ffffffff81269d08: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127cbf0)
Location: fs/statfs.c:148
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_statfs64
```
**Symbols:**

```
ffffffff8127cbf0-ffffffff8127ccb8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a330)
Location: fs/statfs.c:151
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_statfs64
```
**Symbols:**

```
ffffffff8128a330-ffffffff8128a3f8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ace70)
Location: fs/statfs.c:152
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_statfs64
```
**Symbols:**

```
ffffffff812ace70-ffffffff812acf38: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d49b0)
Location: fs/statfs.c:152
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff812d49b0-ffffffff812d4a78: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812e9d80)
Location: fs/statfs.c:152
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff812e9d80-ffffffff812e9e48: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308780)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81308780-ffffffff81308848: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131b820)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff8131b820-ffffffff8131b8e8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813555f0)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff813555f0-ffffffff813556b6: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81361f10)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81361f10-ffffffff81361fd6: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813689f0)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff813689f0-ffffffff81368ab3: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b76f0)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff813b76f0-ffffffff813b77b3: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d010)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff8143d010-ffffffff8143d0dd: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cb7d0)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff814cb7d0-ffffffff814cb89d: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501a10)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81501a10-ffffffff81501add: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536660)
Location: fs/statfs.c:168
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81536660-ffffffff8153672d: do_statfs64 (STB_LOCAL)
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
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d33e8)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffff8000103d33e8-ffff8000103d34b4: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05adaf0)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_fstatfs64
  - fs/statfs.c:__se_sys_statfs64
```
**Symbols:**

```
c05adaf0-c05adc1c: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d5a80)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
c0000000004d5a80-c0000000004d5b18: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028dff8)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffe00028dff8-ffffffe00028e06c: do_statfs64 (STB_LOCAL)
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
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81313e00)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81313e00-ffffffff81313ec8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304a10)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81304a10-ffffffff81304ad8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81311bf0)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81311bf0-ffffffff81311cb8: do_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs *st, struct statfs64 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323430)
Location: fs/statfs.c:166
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_statfs64
```
**Symbols:**

```
ffffffff81323430-ffffffff813234f8: do_statfs64 (STB_LOCAL)
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
