# Function: <code>ata_force_xfermask</code>

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
In drivers/ata/libata-core.c (ffffffff815ce1da)
Location: drivers/ata/libata-core.c:414
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
In drivers/ata/libata-core.c (ffffffff81626d98)
Location: drivers/ata/libata-core.c:417
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
In drivers/ata/libata-core.c (ffffffff81657a02)
Location: drivers/ata/libata-core.c:417
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
In drivers/ata/libata-core.c (ffffffff8166c208)
Location: drivers/ata/libata-core.c:417
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
In drivers/ata/libata-core.c (ffffffff816d585b)
Location: drivers/ata/libata-core.c:417
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
In drivers/ata/libata-core.c (ffffffff817115d6)
Location: drivers/ata/libata-core.c:417
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
In drivers/ata/libata-core.c (ffffffff81733a89)
Location: drivers/ata/libata-core.c:417
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
In drivers/ata/libata-core.c (ffffffff8176f435)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (ffffffff817934a5)
Location: drivers/ata/libata-core.c:401
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
void ata_force_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:403
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81852970-ffffffff81852a2a: ata_force_xfermask (STB_LOCAL)
ffffffff81859194-ffffffff81859204: ata_force_xfermask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ata_force_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:403
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81862cd0-ffffffff81862d8a: ata_force_xfermask (STB_LOCAL)
ffffffff81c171a7-ffffffff81c17217: ata_force_xfermask.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8184aa01)
Location: drivers/ata/libata-core.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff818d7c41)
Location: drivers/ata/libata-core.c:409
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81a28c14)
Location: drivers/ata/libata-core.c:416
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81bab65e)
Location: drivers/ata/libata-core.c:416
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81c0270e)
Location: drivers/ata/libata-core.c:416
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81c5882c)
Location: drivers/ata/libata-core.c:416
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffff80001099d920)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (c0a6df40)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (c000000000a617b4)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (ffffffe0005fda10)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (ffffffff817585b5)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (ffffffff81738455)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (ffffffff81788325)
Location: drivers/ata/libata-core.c:401
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
In drivers/ata/libata-core.c (ffffffff817a2175)
Location: drivers/ata/libata-core.c:401
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
</ul>
