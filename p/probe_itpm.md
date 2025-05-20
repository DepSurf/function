# Function: <code>probe_itpm</code>

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
In drivers/char/tpm/tpm_tis.c (ffffffff815294aa)
Location: drivers/char/tpm/tpm_tis.c:472
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157c6f9)
Location: drivers/char/tpm/tpm_tis_core.c:434
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8c09)
Location: drivers/char/tpm/tpm_tis_core.c:456
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be6bf)
Location: drivers/char/tpm/tpm_tis_core.c:444
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624dfa)
Location: drivers/char/tpm/tpm_tis_core.c:456
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165f0fa)
Location: drivers/char/tpm/tpm_tis_core.c:564
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d5b6)
Location: drivers/char/tpm/tpm_tis_core.c:560
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b437f)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d705f)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
int probe_itpm(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178b58f)
Location: drivers/char/tpm/tpm_tis_core.c:640
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8178b58f-ffffffff8178b695: probe_itpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int probe_itpm(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81c0acb5)
Location: drivers/char/tpm/tpm_tis_core.c:607
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81c0acb5-ffffffff81c0adbb: probe_itpm (STB_LOCAL)
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81bfc73e)
Location: drivers/char/tpm/tpm_tis_core.c:618
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81cfd4da)
Location: drivers/char/tpm/tpm_tis_core.c:619
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81ec5da5)
Location: drivers/char/tpm/tpm_tis_core.c:619
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaf6b0)
Location: drivers/char/tpm/tpm_tis_core.c:633
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int probe_itpm(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afad30)
Location: drivers/char/tpm/tpm_tis_core.c:700
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81afad30-ffffffff81afaf04: probe_itpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int probe_itpm(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4e3c0)
Location: drivers/char/tpm/tpm_tis_core.c:728
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81b4e3c0-ffffffff81b4e594: probe_itpm (STB_LOCAL)
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
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1a3c)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (c09ba7e0)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (c000000000964718)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (ffffffe00057329e)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169caaf)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167a49f)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816cad1f)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e51ef)
Location: drivers/char/tpm/tpm_tis_core.c:559
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
