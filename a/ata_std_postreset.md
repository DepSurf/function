# Function: <code>ata_std_postreset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cea20)
Location: drivers/ata/libata-core.c:3894
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff815cea20-ffffffff815ceb14: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81627600)
Location: drivers/ata/libata-core.c:4070
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81627600-ffffffff816276f4: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81658260)
Location: drivers/ata/libata-core.c:4112
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81658260-ffffffff81658354: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166ca90)
Location: drivers/ata/libata-core.c:4189
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff8166ca90-ffffffff8166cb84: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d60e0)
Location: drivers/ata/libata-core.c:4199
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff816d60e0-ffffffff816d61d4: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4195
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81713c72-ffffffff81713cd9: ata_std_postreset.cold.61 (STB_LOCAL)
ffffffff81711d90-ffffffff81711e27: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4196
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81736121-ffffffff81736188: ata_std_postreset.cold.62 (STB_LOCAL)
ffffffff81734250-ffffffff817342e7: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81771c7c-ffffffff81771ce3: ata_std_postreset.cold (STB_LOCAL)
ffffffff8176fc00-ffffffff8176fc99: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81795c5a-ffffffff81795cc1: ata_std_postreset.cold (STB_LOCAL)
ffffffff81793c70-ffffffff81793d09: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81853700)
Location: drivers/ata/libata-core.c:3572
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81853700-ffffffff81853767: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818639d0)
Location: drivers/ata/libata-core.c:3572
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff818639d0-ffffffff81863a37: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3572
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81c08f75-ffffffff81c08ff0: ata_std_postreset.cold (STB_LOCAL)
ffffffff81846a20-ffffffff81846abd: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3623
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81d0d7f4-ffffffff81d0d800: ata_std_postreset.cold (STB_LOCAL)
ffffffff818d3610-ffffffff818d373e: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a23d70)
Location: drivers/ata/libata-core.c:3654
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81a23d70-ffffffff81a23de9: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba5cf0)
Location: drivers/ata/libata-core.c:3656
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81ba5cf0-ffffffff81ba5d69: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfc830)
Location: drivers/ata/libata-core.c:3849
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81bfc830-ffffffff81bfc8a9: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c52b10)
Location: drivers/ata/libata-core.c:3846
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff81c52b10-ffffffff81c52b89: ata_std_postreset (STB_GLOBAL)
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
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099e098)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libahci.c:ahci_postreset
```
**Symbols:**

```
ffff80001099e098-ffff80001099e1ac: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6e7a0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libahci.c:ahci_postreset
```
**Symbols:**

```
c0a6e7a0-c0a6e8cc: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a62260)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
c000000000a62260-c000000000a623a8: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fe23e)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffe0005fe23e-ffffffe0005fe326: ata_std_postreset (STB_GLOBAL)
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
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff8175ad71-ffffffff8175add8: ata_std_postreset.cold (STB_LOCAL)
ffffffff81758d80-ffffffff81758e19: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff8173ac11-ffffffff8173ac78: ata_std_postreset.cold (STB_LOCAL)
ffffffff81738c20-ffffffff81738cb9: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff8178aada-ffffffff8178ab41: ata_std_postreset.cold (STB_LOCAL)
ffffffff81788af0-ffffffff81788b89: ata_std_postreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ata_std_postreset(struct ata_link *link, unsigned int *classes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4180
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_postreset
```
**Symbols:**

```
ffffffff817a492a-ffffffff817a4991: ata_std_postreset.cold (STB_LOCAL)
ffffffff817a2940-ffffffff817a29d9: ata_std_postreset (STB_GLOBAL)
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
