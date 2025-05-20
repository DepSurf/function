# Function: <code>ata_eh_maybe_retry_flush</code>

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
In drivers/ata/libata-eh.c (ffffffff815d938f)
Location: drivers/ata/libata-eh.c:3347
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81632ffe)
Location: drivers/ata/libata-eh.c:3438
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8166414e)
Location: drivers/ata/libata-eh.c:3438
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81678a89)
Location: drivers/ata/libata-eh.c:3393
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff816e20c9)
Location: drivers/ata/libata-eh.c:3391
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8171e905)
Location: drivers/ata/libata-eh.c:3369
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8174106f)
Location: drivers/ata/libata-eh.c:3365
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8177cabb)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817a0b81)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861c10)
Location: drivers/ata/libata-eh.c:3152
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81861c10-ffffffff81861dca: ata_eh_maybe_retry_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870a20)
Location: drivers/ata/libata-eh.c:3152
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81870a20-ffffffff81870bda: ata_eh_maybe_retry_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81853140)
Location: drivers/ata/libata-eh.c:3153
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81853140-ffffffff818532f7: ata_eh_maybe_retry_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e1180)
Location: drivers/ata/libata-eh.c:3160
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff818e1180-ffffffff818e135b: ata_eh_maybe_retry_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:3162
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81a31130-ffffffff81a3122f: ata_eh_maybe_retry_flush (STB_LOCAL)
ffffffff81ed8492-ffffffff81ed8596: ata_eh_maybe_retry_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb53e0)
Location: drivers/ata/libata-eh.c:3184
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81bb53e0-ffffffff81bb55f7: ata_eh_maybe_retry_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0c8b0)
Location: drivers/ata/libata-eh.c:3294
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81c0c8b0-ffffffff81c0cac7: ata_eh_maybe_retry_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_eh_maybe_retry_flush(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c61a80)
Location: drivers/ata/libata-eh.c:3293
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81c61a80-ffffffff81c61c97: ata_eh_maybe_retry_flush (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffff8000109abfd4)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (c0a7bf38)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (c000000000a73294)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffe0006097cc)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81765c53)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81745ab3)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81795a01)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817af871)
Location: drivers/ata/libata-eh.c:3350
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
