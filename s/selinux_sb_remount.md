# Function: <code>selinux_sb_remount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813475f0)
Location: security/selinux/hooks.c:2610
Inline: False
```
**Symbols:**

```
ffffffff813475f0-ffffffff813478f2: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137f320)
Location: security/selinux/hooks.c:2687
Inline: False
```
**Symbols:**

```
ffffffff8137f320-ffffffff8137f642: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81395db0)
Location: security/selinux/hooks.c:2698
Inline: False
```
**Symbols:**

```
ffffffff81395db0-ffffffff813960d2: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813abea0)
Location: security/selinux/hooks.c:2670
Inline: False
```
**Symbols:**

```
ffffffff813abea0-ffffffff813ac1c6: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813d1f10)
Location: security/selinux/hooks.c:2694
Inline: False
```
**Symbols:**

```
ffffffff813d1f10-ffffffff813d2236: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2838
Inline: False
```
**Symbols:**

```
ffffffff814016c0-ffffffff814019b9: selinux_sb_remount (STB_LOCAL)
ffffffff81402ca4-ffffffff81402cf6: selinux_sb_remount.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2628
Inline: False
```
**Symbols:**

```
ffffffff8141cdf0-ffffffff8141cfb2: selinux_sb_remount (STB_LOCAL)
ffffffff8141e811-ffffffff8141e837: selinux_sb_remount.cold.79 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2680
Inline: False
```
**Symbols:**

```
ffffffff8144a830-ffffffff8144a9e9: selinux_sb_remount (STB_LOCAL)
ffffffff8144c480-ffffffff8144c4a6: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffffffff81464550-ffffffff81464709: selinux_sb_remount (STB_LOCAL)
ffffffff81466270-ffffffff81466296: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2651
Inline: False
```
**Symbols:**

```
ffffffff814b9350-ffffffff814b953f: selinux_sb_remount (STB_LOCAL)
ffffffff814b9e4d-ffffffff814b9f06: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2659
Inline: False
```
**Symbols:**

```
ffffffff814d5f60-ffffffff814d614e: selinux_sb_remount (STB_LOCAL)
ffffffff81bf02d3-ffffffff81bf038c: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2757
Inline: False
```
**Symbols:**

```
ffffffff814dcdd0-ffffffff814dcfcf: selinux_sb_remount (STB_LOCAL)
ffffffff81be24e6-ffffffff81be259f: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2750
Inline: False
```
**Symbols:**

```
ffffffff815362a0-ffffffff8153649f: selinux_sb_remount (STB_LOCAL)
ffffffff81cd3e0f-ffffffff81cd3ec8: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2679
Inline: False
```
**Symbols:**

```
ffffffff815cd560-ffffffff815cd646: selinux_sb_remount (STB_LOCAL)
ffffffff81e86f0f-ffffffff81e86f33: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8167aea0)
Location: security/selinux/hooks.c:2678
Inline: False
```
**Symbols:**

```
ffffffff8167aea0-ffffffff8167afa3: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b35f0)
Location: security/selinux/hooks.c:2657
Inline: False
```
**Symbols:**

```
ffffffff816b35f0-ffffffff816b36f3: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2707
Inline: False
```
**Symbols:**

```
ffffffff816f0160-ffffffff816f030e: selinux_sb_remount (STB_LOCAL)
ffffffff821d069f-ffffffff821d06b4: selinux_sb_remount.cold (STB_LOCAL)
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
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff8000105525f0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffff8000105525f0-ffff8000105527b4: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07048dc)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
c07048dc-c0704afc: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a8ff0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
c0000000006a8ff0-c0000000006a9298: selinux_sb_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003ab534)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffffffe0003ab534-ffffffe0003ab680: selinux_sb_remount (STB_LOCAL)
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
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffffffff8145cb30-ffffffff8145cce9: selinux_sb_remount (STB_LOCAL)
ffffffff8145e850-ffffffff8145e876: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffffffff8144d560-ffffffff8144d719: selinux_sb_remount (STB_LOCAL)
ffffffff8144f280-ffffffff8144f2a6: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffffffff81458bd0-ffffffff81458d89: selinux_sb_remount (STB_LOCAL)
ffffffff8145a8f0-ffffffff8145a916: selinux_sb_remount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int selinux_sb_remount(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2682
Inline: False
```
**Symbols:**

```
ffffffff8146d6e0-ffffffff8146d899: selinux_sb_remount (STB_LOCAL)
ffffffff81472021-ffffffff81472047: selinux_sb_remount.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *mnt_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
