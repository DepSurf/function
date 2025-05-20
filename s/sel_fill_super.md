# Function: <code>sel_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8134a6e0)
Location: security/selinux/selinuxfs.c:1737
Inline: False
```
**Symbols:**

```
ffffffff8134a6e0-ffffffff8134a9ba: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81380220)
Location: security/selinux/selinuxfs.c:1783
Inline: False
```
**Symbols:**

```
ffffffff81380220-ffffffff813804fb: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81396ca0)
Location: security/selinux/selinuxfs.c:1785
Inline: False
```
**Symbols:**

```
ffffffff81396ca0-ffffffff81396f7b: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813ad030)
Location: security/selinux/selinuxfs.c:1793
Inline: False
```
**Symbols:**

```
ffffffff813ad030-ffffffff813ad315: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813d30f0)
Location: security/selinux/selinuxfs.c:1793
Inline: False
```
**Symbols:**

```
ffffffff813d30f0-ffffffff813d33d5: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1896
Inline: False
```
**Symbols:**

```
ffffffff81404dd0-ffffffff8140510c: sel_fill_super (STB_LOCAL)
ffffffff81406006-ffffffff81406033: sel_fill_super.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1896
Inline: False
```
**Symbols:**

```
ffffffff81420690-ffffffff814209db: sel_fill_super (STB_LOCAL)
ffffffff81421b4c-ffffffff81421b79: sel_fill_super.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffff8144e290-ffffffff8144e5ca: sel_fill_super (STB_LOCAL)
ffffffff8144f6ff-ffffffff8144f72f: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffff814680b0-ffffffff814683ea: sel_fill_super (STB_LOCAL)
ffffffff81469577-ffffffff814695a7: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1967
Inline: False
```
**Symbols:**

```
ffffffff814bc3f0-ffffffff814bc7c8: sel_fill_super (STB_LOCAL)
ffffffff814bd731-ffffffff814bd77f: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:2052
Inline: False
```
**Symbols:**

```
ffffffff814d9f00-ffffffff814da359: sel_fill_super (STB_LOCAL)
ffffffff81bf054a-ffffffff81bf0597: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:2055
Inline: False
```
**Symbols:**

```
ffffffff814e1670-ffffffff814e1bac: sel_fill_super (STB_LOCAL)
ffffffff81be26e2-ffffffff81be2727: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:2055
Inline: False
```
**Symbols:**

```
ffffffff8153a5f0-ffffffff8153abab: sel_fill_super (STB_LOCAL)
ffffffff81cd414b-ffffffff81cd4190: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:2059
Inline: False
```
**Symbols:**

```
ffffffff815d1d20-ffffffff815d22e1: sel_fill_super (STB_LOCAL)
ffffffff81e87111-ffffffff81e8715a: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167fb80)
Location: security/selinux/selinuxfs.c:2056
Inline: False
```
**Symbols:**

```
ffffffff8167fb80-ffffffff81680199: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b7c60)
Location: security/selinux/selinuxfs.c:1980
Inline: False
```
**Symbols:**

```
ffffffff816b7c60-ffffffff816b8271: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f3730)
Location: security/selinux/selinuxfs.c:1970
Inline: False
```
**Symbols:**

```
ffffffff816f3730-ffffffff816f3cc6: sel_fill_super (STB_LOCAL)
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
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffff8000105564c8)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffff8000105564c8-ffff800010556870: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c070aaf4)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
c070aaf4-c070ae24: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b5290)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
c0000000006b5290-c0000000006b5724: sel_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003adbd2)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffe0003adbd2-ffffffe0003adee2: sel_fill_super (STB_LOCAL)
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
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffff81460690-ffffffff814609ca: sel_fill_super (STB_LOCAL)
ffffffff81461b57-ffffffff81461b87: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffff814510c0-ffffffff814513fa: sel_fill_super (STB_LOCAL)
ffffffff81452587-ffffffff814525b7: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffff8145c730-ffffffff8145ca6a: sel_fill_super (STB_LOCAL)
ffffffff8145dbf7-ffffffff8145dc27: sel_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sel_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1895
Inline: False
```
**Symbols:**

```
ffffffff81473ed0-ffffffff8147420a: sel_fill_super (STB_LOCAL)
ffffffff81475397-ffffffff814753c7: sel_fill_super.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fs_context *fc</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>int silent</code>
</li>
</ul>
</details>
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
