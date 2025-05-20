# Function: <code>aa_label_xprintk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138cf50)
Location: security/apparmor/label.c:1759
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff8138cf50-ffffffff8138d105: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c7cf0)
Location: security/apparmor/label.c:1774
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff813c7cf0-ffffffff813c7ea8: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813df2d0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff813df2d0-ffffffff813df488: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813eebf0)
Location: security/apparmor/label.c:1764
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff813eebf0-ffffffff813eed60: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814168a0)
Location: security/apparmor/label.c:1764
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff814168a0-ffffffff81416a10: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1763
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81449d4c-ffffffff81449d6a: aa_label_xprintk.cold.12 (STB_LOCAL)
ffffffff81448c90-ffffffff81448dde: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1764
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81466cb0-ffffffff81466cce: aa_label_xprintk.cold.12 (STB_LOCAL)
ffffffff81465bc0-ffffffff81465d0e: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1760
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81493d77-ffffffff81493d95: aa_label_xprintk.cold (STB_LOCAL)
ffffffff81493190-ffffffff814932df: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff814adca7-ffffffff814adcc5: aa_label_xprintk.cold (STB_LOCAL)
ffffffff814ad0c0-ffffffff814ad20f: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1786
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff8150cca7-ffffffff8150ccdb: aa_label_xprintk.cold (STB_LOCAL)
ffffffff8150baf0-ffffffff8150bc00: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1786
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81bf17d0-ffffffff81bf1804: aa_label_xprintk.cold (STB_LOCAL)
ffffffff815289a0-ffffffff81528ab0: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1786
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81be37e0-ffffffff81be3816: aa_label_xprintk.cold (STB_LOCAL)
ffffffff8152eb10-ffffffff8152ec20: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1786
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81cd675b-ffffffff81cd67a6: aa_label_xprintk.cold (STB_LOCAL)
ffffffff8158cf20-ffffffff8158d03c: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1795
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81e896b1-ffffffff81e896fa: aa_label_xprintk.cold (STB_LOCAL)
ffffffff8162e190-ffffffff8162e2bc: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e2cd0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff816e2cd0-ffffffff816e2e41: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171c260)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff8171c260-ffffffff8171c3b3: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8175acb0)
Location: security/apparmor/label.c:1795
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff8175acb0-ffffffff8175ae03: aa_label_xprintk (STB_GLOBAL)
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
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a44d8)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffff8000105a44d8-ffff8000105a467c: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c07545e8)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
c07545e8-c0754794: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c000000000720020)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
c000000000720020-c00000000072023c: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ee5c0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffe0003ee5c0-ffffffe0003ee71e: aa_label_xprintk (STB_GLOBAL)
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
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff814a6287-ffffffff814a62a5: aa_label_xprintk.cold (STB_LOCAL)
ffffffff814a56a0-ffffffff814a57ef: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff81496ca7-ffffffff81496cc5: aa_label_xprintk.cold (STB_LOCAL)
ffffffff814960c0-ffffffff8149620f: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff814a2327-ffffffff814a2345: aa_label_xprintk.cold (STB_LOCAL)
ffffffff814a1740-ffffffff814a188f: aa_label_xprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void aa_label_xprintk(struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1789
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
```
**Symbols:**

```
ffffffff814baae7-ffffffff814bab05: aa_label_xprintk.cold (STB_LOCAL)
ffffffff814b9e60-ffffffff814b9faf: aa_label_xprintk (STB_GLOBAL)
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
