# Function: <code>ata_do_set_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cdf70)
Location: drivers/ata/libata-core.c:3301
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff815cdf70-ffffffff815ce9b5: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81626b40)
Location: drivers/ata/libata-core.c:3476
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81626b40-ffffffff81627596: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816577a0)
Location: drivers/ata/libata-core.c:3518
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff816577a0-ffffffff81658200: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166bfb0)
Location: drivers/ata/libata-core.c:3595
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff8166bfb0-ffffffff8166ca24: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d5600)
Location: drivers/ata/libata-core.c:3604
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff816d5600-ffffffff816d607d: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3600
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81713b60-ffffffff81713c72: ata_do_set_mode.cold.60 (STB_LOCAL)
ffffffff817113c0-ffffffff81711d21: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3600
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff8173600f-ffffffff81736121: ata_do_set_mode.cold.61 (STB_LOCAL)
ffffffff81733870-ffffffff817341f0: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81771b38-ffffffff81771c7c: ata_do_set_mode.cold (STB_LOCAL)
ffffffff8176f1f0-ffffffff8176fb94: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81795b13-ffffffff81795c5a: ata_do_set_mode.cold (STB_LOCAL)
ffffffff81793260-ffffffff81793c04: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3294
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81859f14-ffffffff81859f34: ata_do_set_mode.cold (STB_LOCAL)
ffffffff81857e90-ffffffff8185819b: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3294
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81c17f27-ffffffff81c17f47: ata_do_set_mode.cold (STB_LOCAL)
ffffffff818680f0-ffffffff818683fb: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3294
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81c09c24-ffffffff81c09cb3: ata_do_set_mode.cold (STB_LOCAL)
ffffffff8184a970-ffffffff8184ad1c: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3345
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81d0e3b1-ffffffff81d0e440: ata_do_set_mode.cold (STB_LOCAL)
ffffffff818d7bb0-ffffffff818d7f5c: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3376
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81ed72a9-ffffffff81ed7343: ata_do_set_mode.cold (STB_LOCAL)
ffffffff81a28b80-ffffffff81a28f57: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bab5d0)
Location: drivers/ata/libata-core.c:3378
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81bab5d0-ffffffff81baba29: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c02680)
Location: drivers/ata/libata-core.c:3571
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81c02680-ffffffff81c02ad7: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c586d0)
Location: drivers/ata/libata-core.c:3568
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff81c586d0-ffffffff81c58a9f: ata_do_set_mode (STB_GLOBAL)
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
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099d700)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffff80001099d700-ffff80001099e020: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6dcc0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
c0a6dcc0-c0a6e728: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a61520)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
c000000000a61520-c000000000a621c4: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fd9a8)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffe0005fd9a8-ffffffe0005fe1f4: ata_do_set_mode (STB_GLOBAL)
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
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff8175ac2a-ffffffff8175ad71: ata_do_set_mode.cold (STB_LOCAL)
ffffffff81758370-ffffffff81758d14: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff8173aaca-ffffffff8173ac11: ata_do_set_mode.cold (STB_LOCAL)
ffffffff81738210-ffffffff81738bb4: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff8178a993-ffffffff8178aada: ata_do_set_mode.cold (STB_LOCAL)
ffffffff817880e0-ffffffff81788a84: ata_do_set_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_do_set_mode(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3584
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_set_mode
```
**Symbols:**

```
ffffffff817a47e3-ffffffff817a492a: ata_do_set_mode.cold (STB_LOCAL)
ffffffff817a1f30-ffffffff817a28d4: ata_do_set_mode (STB_GLOBAL)
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
