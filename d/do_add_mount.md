# Function: <code>do_add_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122e070)
Location: fs/namespace.c:2331
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8122e070-ffffffff8122e13a: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81256860)
Location: fs/namespace.c:2334
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff81256860-ffffffff8125692f: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126a4b0)
Location: fs/namespace.c:2453
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff8126a4b0-ffffffff8126a57f: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81277c30)
Location: fs/namespace.c:2395
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff81277c30-ffffffff81277d05: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129a670)
Location: fs/namespace.c:2460
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff8129a670-ffffffff8129a745: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c0740)
Location: fs/namespace.c:2491
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff812c0740-ffffffff812c0811: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d5990)
Location: fs/namespace.c:2461
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff812d5990-ffffffff812d5a61: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f3b70)
Location: fs/namespace.c:2678
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff812f3b70-ffffffff812f3c40: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81305720)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff81305720-ffffffff813057f0: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133f060)
Location: fs/namespace.c:2768
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
```
**Symbols:**

```
ffffffff8133f060-ffffffff8133f0e6: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134b0c0)
Location: fs/namespace.c:2774
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
```
**Symbols:**

```
ffffffff8134b0c0-ffffffff8134b146: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81351970)
Location: fs/namespace.c:2807
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff81351970-ffffffff813519f6: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139fce0)
Location: fs/namespace.c:2881
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8139fce0-ffffffff8139fd66: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, const struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814232d0)
Location: fs/namespace.c:2924
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814232d0-ffffffff8142339e: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, const struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814afa10)
Location: fs/namespace.c:3029
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814afa10-ffffffff814afade: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, const struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e4a40)
Location: fs/namespace.c:3220
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814e4a40-ffffffff814e4b0e: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct mountpoint *mp, const struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81518860)
Location: fs/namespace.c:3231
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff81518860-ffffffff8151892e: do_add_mount (STB_LOCAL)
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
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b8e28)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffff8000103b8e28-ffff8000103b8f1c: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05967a4)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
c05967a4-c0596894: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b5f40)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
c0000000004b5f40-c0000000004b6078: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027b1ea)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffe00027b1ea-ffffffe00027b2a4: do_add_mount (STB_LOCAL)
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
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fdd00)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff812fdd00-ffffffff812fddd0: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ee920)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff812ee920-ffffffff812ee9f0: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fbaf0)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff812fbaf0-ffffffff812fbbc0: do_add_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_add_mount(struct mount *newmnt, struct path *path, int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130ce10)
Location: fs/namespace.c:2709
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
```
**Symbols:**

```
ffffffff8130ce10-ffffffff8130cee0: do_add_mount (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mountpoint *mp</code>
</li>
<li>
<b>Param reordered. </b>
<code>newmnt, path, mnt_flags</code> ➡️ <code>newmnt, mp, path, mnt_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
