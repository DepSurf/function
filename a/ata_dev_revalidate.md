# Function: <code>ata_dev_revalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cddd0)
Location: drivers/ata/libata-core.c:4007
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff815cddd0-ffffffff815cdf6c: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816269c0)
Location: drivers/ata/libata-core.c:4183
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff816269c0-ffffffff81626b3c: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81657620)
Location: drivers/ata/libata-core.c:4225
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81657620-ffffffff8165779c: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166be30)
Location: drivers/ata/libata-core.c:4302
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8166be30-ffffffff8166bfa7: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d5480)
Location: drivers/ata/libata-core.c:4312
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff816d5480-ffffffff816d55f7: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4308
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81713a7a-ffffffff81713b60: ata_dev_revalidate.cold.59 (STB_LOCAL)
ffffffff81711300-ffffffff817113b4: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4309
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81735f29-ffffffff8173600f: ata_dev_revalidate.cold.60 (STB_LOCAL)
ffffffff817337b0-ffffffff81733864: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81771a4e-ffffffff81771b38: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff8176f130-ffffffff8176f1e8: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81795a29-ffffffff81795b13: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff817931a0-ffffffff81793258: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81859db6-ffffffff81859ea0: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff81857a80-ffffffff81857b38: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c17dc9-ffffffff81c17eb3: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff81867d00-ffffffff81867db8: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c09acc-ffffffff81c09bb0: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff8184a570-ffffffff8184a63c: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3737
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81d0e27e-ffffffff81d0e362: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff818d7760-ffffffff818d782c: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3764
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81ed7139-ffffffff81ed7254: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff81a28650-ffffffff81a28756: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81baaf70)
Location: drivers/ata/libata-core.c:3766
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81baaf70-ffffffff81bab15d: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c02060)
Location: drivers/ata/libata-core.c:3959
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c02060-ffffffff81c0220d: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c580f0)
Location: drivers/ata/libata-core.c:3956
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c580f0-ffffffff81c5829d: ata_dev_revalidate (STB_GLOBAL)
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
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099d558)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffff80001099d558-ffff80001099d700: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6daa8)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
c0a6daa8-c0a6dcc0: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a61350)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
c000000000a61350-c000000000a61518: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fd846)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffe0005fd846-ffffffe0005fd9a8: ata_dev_revalidate (STB_GLOBAL)
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
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8175ab40-ffffffff8175ac2a: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff817582b0-ffffffff81758368: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8173a9e0-ffffffff8173aaca: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff81738150-ffffffff81738208: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8178a8a9-ffffffff8178a993: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff81788020-ffffffff817880d8: ata_dev_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_dev_revalidate(struct ata_device *dev, unsigned int new_class, unsigned int readid_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4293
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff817a46f9-ffffffff817a47e3: ata_dev_revalidate.cold (STB_LOCAL)
ffffffff817a1e70-ffffffff817a1f28: ata_dev_revalidate (STB_GLOBAL)
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
