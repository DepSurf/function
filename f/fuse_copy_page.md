# Function: <code>fuse_copy_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130e6b0)
Location: fs/fuse/dev.c:976
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_args
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8130e6b0-ffffffff8130ecb2: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81342a20)
Location: fs/fuse/dev.c:951
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81342a20-ffffffff813430c3: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81358850)
Location: fs/fuse/dev.c:954
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81358850-ffffffff81358edc: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136d0b0)
Location: fs/fuse/dev.c:953
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff8136d0b0-ffffffff8136d6e3: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81391c10)
Location: fs/fuse/dev.c:953
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81391c10-ffffffff813922b3: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:966
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff813c0c40-ffffffff813c1257: fuse_copy_page (STB_LOCAL)
ffffffff813c40f3-ffffffff813c417b: fuse_copy_page.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:1020
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff813d9fa0-ffffffff813da5b9: fuse_copy_page (STB_LOCAL)
ffffffff813dd8d3-ffffffff813dd95d: fuse_copy_page.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81406130)
Location: fs/fuse/dev.c:1044
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81406130-ffffffff8140638b: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81420c90)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81420c90-ffffffff81420eeb: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146fd00)
Location: fs/fuse/dev.c:909
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff8146fd00-ffffffff8146ffb8: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148a5a0)
Location: fs/fuse/dev.c:930
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff8148a5a0-ffffffff8148a8b8: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81490070)
Location: fs/fuse/dev.c:927
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81490070-ffffffff81490387: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e7b00)
Location: fs/fuse/dev.c:933
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff814e7b00-ffffffff814e7e19: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81576080)
Location: fs/fuse/dev.c:925
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81576080-ffffffff815763b2: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161b180)
Location: fs/fuse/dev.c:926
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff8161b180-ffffffff8161b463: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816532f0)
Location: fs/fuse/dev.c:928
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff816532f0-ffffffff816535de: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168c900)
Location: fs/fuse/dev.c:928
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff8168c900-ffffffff8168cbe5: fuse_copy_page (STB_LOCAL)
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
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010503940)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffff800010503940-ffff800010503bec: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06bffd8)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
c06bffd8-c06c0270: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c0000000006485d0)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
c0000000006485d0-c000000000648998: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe0003706e4)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffe0003706e4-ffffffe000370904: fuse_copy_page (STB_LOCAL)
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
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81419270)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81419270-ffffffff814194cb: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81409cf0)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81409cf0-ffffffff81409f4b: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81415410)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff81415410-ffffffff8141566b: fuse_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state *cs, struct page **pagep, unsigned int offset, unsigned int count, int zeroing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142c180)
Location: fs/fuse/dev.c:910
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_args
```
**Symbols:**

```
ffffffff8142c180-ffffffff8142c415: fuse_copy_page (STB_LOCAL)
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
