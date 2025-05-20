# Function: <code>tpm_tis_probe_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81529594)
Location: drivers/char/tpm/tpm_tis.c:628
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157c852)
Location: drivers/char/tpm/tpm_tis_core.c:602
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8d4e)
Location: drivers/char/tpm/tpm_tis_core.c:630
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be904)
Location: drivers/char/tpm/tpm_tis_core.c:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624f06)
Location: drivers/char/tpm/tpm_tis_core.c:639
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165f38f)
Location: drivers/char/tpm/tpm_tis_core.c:747
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d84b)
Location: drivers/char/tpm/tpm_tis_core.c:743
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b457e)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d725e)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tpm_tis_probe_irq(struct tpm_chip *chip, u32 intmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178b45e)
Location: drivers/char/tpm/tpm_tis_core.c:823
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8178b45e-ffffffff8178b4fe: tpm_tis_probe_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tpm_tis_probe_irq(struct tpm_chip *chip, u32 intmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81c0ab8c)
Location: drivers/char/tpm/tpm_tis_core.c:800
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81c0ab8c-ffffffff81c0ac2c: tpm_tis_probe_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81bfc8e3)
Location: drivers/char/tpm/tpm_tis_core.c:809
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81cfd67e)
Location: drivers/char/tpm/tpm_tis_core.c:810
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81ec5fe3)
Location: drivers/char/tpm/tpm_tis_core.c:810
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aafb47)
Location: drivers/char/tpm/tpm_tis_core.c:828
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb99a)
Location: drivers/char/tpm/tpm_tis_core.c:961
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4f02a)
Location: drivers/char/tpm/tpm_tis_core.c:989
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1cac)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09babf4)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000964a44)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000573682)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169ccae)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167a69e)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816caf1e)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e53ee)
Location: drivers/char/tpm/tpm_tis_core.c:742
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
