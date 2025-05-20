# Function: <code>sb_finish_set_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813456d0)
Location: security/selinux/hooks.c:426
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813456d0-ffffffff81345909: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137afb0)
Location: security/selinux/hooks.c:497
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8137afb0-ffffffff8137b1f6: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81391400)
Location: security/selinux/hooks.c:498
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81391400-ffffffff81391640: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a55b0)
Location: security/selinux/hooks.c:440
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813a55b0-ffffffff813a580b: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cb0b0)
Location: security/selinux/hooks.c:441
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813cb0b0-ffffffff813cb30b: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:519
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813ff280-ffffffff813ff4d0: sb_finish_set_opts (STB_LOCAL)
ffffffff81402b9c-ffffffff81402be7: sb_finish_set_opts.cold.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:512
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8141b3b0-ffffffff8141b600: sb_finish_set_opts (STB_LOCAL)
ffffffff8141e745-ffffffff8141e790: sb_finish_set_opts.cold.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:535
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81448d90-ffffffff81448fd3: sb_finish_set_opts (STB_LOCAL)
ffffffff8144c343-ffffffff8144c3a3: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81462920-ffffffff81462b63: sb_finish_set_opts (STB_LOCAL)
ffffffff81466133-ffffffff81466193: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:486
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814b6870-ffffffff814b6a04: sb_finish_set_opts (STB_LOCAL)
ffffffff814b9da5-ffffffff814b9e05: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:487
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814d4570-ffffffff814d46dd: sb_finish_set_opts (STB_LOCAL)
ffffffff81bf024f-ffffffff81bf02af: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:565
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814dab50-ffffffff814daddf: sb_finish_set_opts (STB_LOCAL)
ffffffff81be22ce-ffffffff81be23ba: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:542
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81533a50-ffffffff81533ce3: sb_finish_set_opts (STB_LOCAL)
ffffffff81cd3ad7-ffffffff81cd3be0: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:526
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff815ca240-ffffffff815ca4f3: sb_finish_set_opts (STB_LOCAL)
ffffffff81e86c0a-ffffffff81e86cfd: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:528
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81677470-ffffffff816777b0: sb_finish_set_opts (STB_LOCAL)
ffffffff820736e2-ffffffff820736fc: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:520
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff816af760-ffffffff816afa9e: sb_finish_set_opts (STB_LOCAL)
ffffffff820f32db-ffffffff820f32f5: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:561
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff816ec6d0-ffffffff816eca0e: sb_finish_set_opts (STB_LOCAL)
ffffffff821d043d-ffffffff821d0457: sb_finish_set_opts.cold (STB_LOCAL)
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
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010550728)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffff800010550728-ffff800010550a3c: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0703288)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c0703288-c0703524: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a5f80)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c0000000006a5f80-c0000000006a6aa0: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a9c54)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffe0003a9c54-ffffffe0003a9f0c: sb_finish_set_opts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8145af00-ffffffff8145b143: sb_finish_set_opts (STB_LOCAL)
ffffffff8145e713-ffffffff8145e773: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8144b930-ffffffff8144bb73: sb_finish_set_opts (STB_LOCAL)
ffffffff8144f143-ffffffff8144f1a3: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81456fa0-ffffffff814571e3: sb_finish_set_opts (STB_LOCAL)
ffffffff8145a7b3-ffffffff8145a813: sb_finish_set_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sb_finish_set_opts(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:537
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8146bf30-ffffffff8146c16f: sb_finish_set_opts (STB_LOCAL)
ffffffff81471f2e-ffffffff81471f8e: sb_finish_set_opts.cold (STB_LOCAL)
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
