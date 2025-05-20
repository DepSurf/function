# Function: <code>ata_eh_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d61c0)
Location: drivers/ata/libata-eh.c:1446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815d61c0-ffffffff815d61dc: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81632766)
Location: drivers/ata/libata-eh.c:1446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8162fc20-ffffffff8162fc3c: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816638b6)
Location: drivers/ata/libata-eh.c:1446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81660d70-ffffffff81660d8c: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816785e5)
Location: drivers/ata/libata-eh.c:1447
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81675d60-ffffffff81675d7c: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816e1c25)
Location: drivers/ata/libata-eh.c:1445
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816df3b0-ffffffff816df3cc: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171e548)
Location: drivers/ata/libata-eh.c:1396
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8171bbb0-ffffffff8171bbcc: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81740e28)
Location: drivers/ata/libata-eh.c:1392
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8173e480-ffffffff8173e49c: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8177ca62)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8177a340-ffffffff8177a359: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817a07c6)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8179de80-ffffffff8179de99: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8186517c)
Location: drivers/ata/libata-eh.c:1307
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
**Symbols:**

```
ffffffff81862eb0-ffffffff81862ec9: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81873f7c)
Location: drivers/ata/libata-eh.c:1307
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
**Symbols:**

```
ffffffff81871cc0-ffffffff81871cd9: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8185661f)
Location: drivers/ata/libata-eh.c:1307
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff818543c0-ffffffff818543d9: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e4d2a)
Location: drivers/ata/libata-eh.c:1315
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff818e2840-ffffffff818e2859: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a334c0)
Location: drivers/ata/libata-eh.c:1313
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
**Symbols:**

```
ffffffff81a334c0-ffffffff81a33556: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb7c50)
Location: drivers/ata/libata-eh.c:1312
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
**Symbols:**

```
ffffffff81bb7c50-ffffffff81bb7ce6: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0f290)
Location: drivers/ata/libata-eh.c:1315
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
**Symbols:**

```
ffffffff81c0f290-ffffffff81c0f326: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c644d0)
Location: drivers/ata/libata-eh.c:1322
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
**Symbols:**

```
ffffffff81c644d0-ffffffff81c64566: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109ac688)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffff8000109a9868-ffff8000109a98b0: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a7c11c)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c0a79078-c0a7909c: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a73a38)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a70310-c000000000a7032c: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000609d9c)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe000607438-ffffffe000607476: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817658ad)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81762f70-ffffffff81762f89: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8174570d)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81742dd0-ffffffff81742de9: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81795646)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81792d00-ffffffff81792d19: ata_eh_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_done(struct ata_link *link, struct ata_device *dev, unsigned int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817af4b6)
Location: drivers/ata/libata-eh.c:1375
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff817acb40-ffffffff817acb59: ata_eh_done (STB_GLOBAL)
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
