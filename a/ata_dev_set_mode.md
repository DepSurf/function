# Function: <code>ata_dev_set_mode</code>

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
In drivers/ata/libata-core.c (ffffffff815ce495)
Location: drivers/ata/libata-core.c:3203
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8162705c)
Location: drivers/ata/libata-core.c:3378
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81657cc6)
Location: drivers/ata/libata-core.c:3420
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8166c4d8)
Location: drivers/ata/libata-core.c:3497
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff816d5b31)
Location: drivers/ata/libata-core.c:3506
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81711854)
Location: drivers/ata/libata-core.c:3500
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81733d0e)
Location: drivers/ata/libata-core.c:3500
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8176f6d0)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81793740)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3194
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81857b40-ffffffff81857e88: ata_dev_set_mode (STB_LOCAL)
ffffffff81859ea0-ffffffff81859f14: ata_dev_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3194
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81867dc0-ffffffff818680e7: ata_dev_set_mode (STB_LOCAL)
ffffffff81c17eb3-ffffffff81c17f27: ata_dev_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3194
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff8184a640-ffffffff8184a969: ata_dev_set_mode (STB_LOCAL)
ffffffff81c09bb0-ffffffff81c09c24: ata_dev_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3245
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff818d7830-ffffffff818d7ba6: ata_dev_set_mode (STB_LOCAL)
ffffffff81d0e362-ffffffff81d0e3b1: ata_dev_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3276
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81a28760-ffffffff81a28b75: ata_dev_set_mode (STB_LOCAL)
ffffffff81ed7254-ffffffff81ed72a9: ata_dev_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bab170)
Location: drivers/ata/libata-core.c:3278
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81bab170-ffffffff81bab5bf: ata_dev_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c02220)
Location: drivers/ata/libata-core.c:3471
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81c02220-ffffffff81c0266f: ata_dev_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_dev_set_mode(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c582b0)
Location: drivers/ata/libata-core.c:3468
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81c582b0-ffffffff81c586b8: ata_dev_set_mode (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff80001099db3c)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (c0a6e1b4)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (c000000000a61b44)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffe0005fde6a)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81758850)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff817386f0)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff817885c0)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff817a2410)
Location: drivers/ata/libata-core.c:3484
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
