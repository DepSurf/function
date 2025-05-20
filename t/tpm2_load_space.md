# Function: <code>tpm2_load_space</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc45b)
Location: drivers/char/tpm/tpm2-space.c:177
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816228fb)
Location: drivers/char/tpm/tpm2-space.c:177
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff8165c79a)
Location: drivers/char/tpm/tpm2-space.c:180
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81679b0a)
Location: drivers/char/tpm/tpm2-space.c:178
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816b01de)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816d2ede)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm2_load_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81787100-ffffffff817871f9: tpm2_load_space (STB_LOCAL)
ffffffff81787808-ffffffff81787842: tpm2_load_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm2_load_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff8179e210-ffffffff8179e309: tpm2_load_space (STB_LOCAL)
ffffffff81c0a84f-ffffffff81c0a889: tpm2_load_space.cold (STB_LOCAL)
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
In drivers/char/tpm/tpm2-space.c (ffffffff81780ccd)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81807178)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81946d88)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81aaa098)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81af58b8)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81b48ea8)
Location: drivers/char/tpm/tpm2-space.c:176
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffff8000108bdae8)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (c09b6f38)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (c00000000095fac0)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffe000570000)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff8169892e)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff8167631e)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816c6b9e)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816e108e)
Location: drivers/char/tpm/tpm2-space.c:173
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
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
