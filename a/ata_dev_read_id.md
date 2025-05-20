# Function: <code>ata_dev_read_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cbe30)
Location: drivers/ata/libata-core.c:1849
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff815cbe30-ffffffff815cc3c3: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81624610)
Location: drivers/ata/libata-core.c:1852
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81624610-ffffffff81624bcb: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816551b0)
Location: drivers/ata/libata-core.c:1861
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff816551b0-ffffffff8165576b: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81669c70)
Location: drivers/ata/libata-core.c:1861
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81669c70-ffffffff8166a239: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d32c0)
Location: drivers/ata/libata-core.c:1861
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff816d32c0-ffffffff816d388c: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1852
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8171325b-ffffffff81713384: ata_dev_read_id.cold.56 (STB_LOCAL)
ffffffff8170f6d0-ffffffff8170fb64: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1852
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8173570a-ffffffff81735833: ata_dev_read_id.cold.57 (STB_LOCAL)
ffffffff81731b80-ffffffff81732014: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81771224-ffffffff8177135b: ata_dev_read_id.cold (STB_LOCAL)
ffffffff8176d6a0-ffffffff8176db30: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff817951ff-ffffffff81795336: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81791710-ffffffff81791ba0: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1782
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff8185973e-ffffffff8185987c: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81856950-ffffffff81856dec: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1782
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c17751-ffffffff81c1788f: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81866bd0-ffffffff8186706c: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1782
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c0933e-ffffffff81c09479: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81848fc0-ffffffff81849462: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1785
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81d0db8b-ffffffff81d0dcc6: ata_dev_read_id.cold (STB_LOCAL)
ffffffff818d6020-ffffffff818d64c2: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1760
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81ed6b70-ffffffff81ed6c86: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81a26d90-ffffffff81a27342: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba9100)
Location: drivers/ata/libata-core.c:1760
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81ba9100-ffffffff81ba97c0: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c00190)
Location: drivers/ata/libata-core.c:1794
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c00190-ffffffff81c00815: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c56200)
Location: drivers/ata/libata-core.c:1789
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c56200-ffffffff81c56885: ata_dev_read_id (STB_GLOBAL)
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
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099b5e8)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffff80001099b5e8-ffff80001099bb60: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6b3e0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
c0a6b3e0-c0a6b9cc: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5edc0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
c000000000a5edc0-c000000000a5f454: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fbb56)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffe0005fbb56-ffffffe0005fbff2: ata_dev_read_id (STB_GLOBAL)
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
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8175a30f-ffffffff8175a446: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81756850-ffffffff81756ce0: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8173a1af-ffffffff8173a2e6: ata_dev_read_id.cold (STB_LOCAL)
ffffffff817366f0-ffffffff81736b80: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8178a07f-ffffffff8178a1b6: ata_dev_read_id.cold (STB_LOCAL)
ffffffff81786590-ffffffff81786a20: ata_dev_read_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_dev_read_id(struct ata_device *dev, unsigned int *p_class, unsigned int flags, u16 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1836
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff817a3ecf-ffffffff817a4006: ata_dev_read_id.cold (STB_LOCAL)
ffffffff817a03e0-ffffffff817a0870: ata_dev_read_id (STB_GLOBAL)
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
