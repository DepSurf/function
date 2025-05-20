# Function: <code>security_fs_use</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358f10)
Location: security/selinux/ss/services.c:2544
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81358f10-ffffffff813590d1: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138ee80)
Location: security/selinux/ss/services.c:2538
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8138ee80-ffffffff8138f060: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5aa0)
Location: security/selinux/ss/services.c:2538
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813a5aa0-ffffffff813a5c80: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bc510)
Location: security/selinux/ss/services.c:2654
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813bc510-ffffffff813bc6f7: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e2680)
Location: security/selinux/ss/services.c:2664
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813e2680-ffffffff813e2867: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814134e0)
Location: security/selinux/ss/services.c:2763
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814134e0-ffffffff814136d6: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142fa00)
Location: security/selinux/ss/services.c:2729
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8142fa00-ffffffff8142fc0c: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145d3b0)
Location: security/selinux/ss/services.c:2742
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8145d3b0-ffffffff8145d5b9: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81477160)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81477160-ffffffff81477369: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cc6c0)
Location: security/selinux/ss/services.c:2792
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814cc6c0-ffffffff814cc7d9: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9ac0)
Location: security/selinux/ss/services.c:2884
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814e9ac0-ffffffff814e9bd1: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f0660)
Location: security/selinux/ss/services.c:2952
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814f0660-ffffffff814f0798: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81cd50d0-ffffffff81cd50e5: security_fs_use.cold (STB_LOCAL)
ffffffff8154abc0-ffffffff8154ad46: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2966
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81e87f1c-ffffffff81e87f31: security_fs_use.cold (STB_LOCAL)
ffffffff815e38e0-ffffffff815e3a74: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2959
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff82073e05-ffffffff82073e1a: security_fs_use.cold (STB_LOCAL)
ffffffff81692b80-ffffffff81692d14: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2906
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff820f39b7-ffffffff820f39cb: security_fs_use.cold (STB_LOCAL)
ffffffff816cb0e0-ffffffff816cb25d: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_fs_use(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2915
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff821d0b7d-ffffffff821d0b91: security_fs_use.cold (STB_LOCAL)
ffffffff81707d20-ffffffff81707e9d: security_fs_use (STB_GLOBAL)
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
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010566d30)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffff800010566d30-ffff800010566f5c: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071b344)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c071b344-c071b524: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c9d70)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c0000000006c9d70-c0000000006ca290: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bcc36)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffe0003bcc36-ffffffe0003bcdb4: security_fs_use (STB_GLOBAL)
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
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146f740)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8146f740-ffffffff8146f949: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81460160)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81460160-ffffffff81460369: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b7e0)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8146b7e0-ffffffff8146b9e9: security_fs_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_fs_use(struct selinux_state *state, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81482f90)
Location: security/selinux/ss/services.c:2749
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81482f90-ffffffff8148318a: security_fs_use (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb</code> ➡️ <code>state, sb</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, sb</code> ➡️ <code>sb</code>
</li>
</ul>
</details>
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
