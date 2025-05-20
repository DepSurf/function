# Function: <code>do_quotactl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81275c6e)
Location: fs/quota/quota.c:640
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812a243e)
Location: fs/quota/quota.c:696
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812b7e18)
Location: fs/quota/quota.c:698
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812c516a)
Location: fs/quota/quota.c:698
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812e900a)
Location: fs/quota/quota.c:699
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81315bb5)
Location: fs/quota/quota.c:700
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
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
In fs/quota/quota.c (ffffffff8132cb47)
Location: fs/quota/quota.c:698
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81354660)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81354660-ffffffff81354d55: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8136c9d0)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff8136c9d0-ffffffff8136d0c5: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b4870)
Location: fs/quota/quota.c:682
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff813b4870-ffffffff813b4eb7: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c6290)
Location: fs/quota/quota.c:764
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff813c6290-ffffffff813c6902: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813ccf90)
Location: fs/quota/quota.c:766
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff813ccf90-ffffffff813cd59a: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141e250)
Location: fs/quota/quota.c:766
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff8141e250-ffffffff8141e874: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81495f40)
Location: fs/quota/quota.c:767
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81495f40-ffffffff814965c5: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81529ea0)
Location: fs/quota/quota.c:767
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81529ea0-ffffffff8152a525: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81562270)
Location: fs/quota/quota.c:767
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81562270-ffffffff81562908: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81598960)
Location: fs/quota/quota.c:767
Inline: False
Direct callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81598960-ffffffff81598ff8: do_quotactl (STB_LOCAL)
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
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffff8000104368a8)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffff8000104368a8-ffff800010436fac: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c05fe4d0)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c05fe4d0-c05fec64: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c000000000548ac0)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c000000000548ac0-c0000000005492ac: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffe0002d0e8c)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffe0002d0e8c-ffffffe0002d130e: do_quotactl (STB_LOCAL)
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
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81364fb0)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81364fb0-ffffffff813656a5: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81355c50)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81355c50-ffffffff81356345: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81362a80)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81362a80-ffffffff81363175: do_quotactl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_quotactl(struct super_block *sb, int type, int cmd, qid_t id, void *addr, const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81376130)
Location: fs/quota/quota.c:684
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81376130-ffffffff81376825: do_quotactl (STB_LOCAL)
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
