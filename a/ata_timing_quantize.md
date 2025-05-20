# Function: <code>ata_timing_quantize</code>

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
In drivers/ata/libata-core.c (ffffffff815c8398)
Location: drivers/ata/libata-core.c:2945
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff81622258)
Location: drivers/ata/libata-core.c:3120
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff81652dd8)
Location: drivers/ata/libata-core.c:3162
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff81667518)
Location: drivers/ata/libata-core.c:3239
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff816d0b78)
Location: drivers/ata/libata-core.c:3247
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff8170d268)
Location: drivers/ata/libata-core.c:3241
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff8172f6e8)
Location: drivers/ata/libata-core.c:3241
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff8176ae68)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff8178eed8)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_timing_quantize(const struct ata_timing *t, struct ata_timing *q, int T, int UT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pata-timings.c (ffffffff8186f860)
Location: drivers/ata/libata-pata-timings.c:60
Inline: False
Direct callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
```
**Symbols:**

```
ffffffff8186f860-ffffffff8186f972: ata_timing_quantize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_timing_quantize(const struct ata_timing *t, struct ata_timing *q, int T, int UT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pata-timings.c (ffffffff8187e530)
Location: drivers/ata/libata-pata-timings.c:60
Inline: False
Direct callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
```
**Symbols:**

```
ffffffff8187e530-ffffffff8187e642: ata_timing_quantize (STB_LOCAL)
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
In drivers/ata/libata-pata-timings.c (ffffffff81860f61)
Location: drivers/ata/libata-pata-timings.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
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
In drivers/ata/libata-pata-timings.c (ffffffff818efd81)
Location: drivers/ata/libata-pata-timings.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
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
In drivers/ata/libata-pata-timings.c (ffffffff81a41fc8)
Location: drivers/ata/libata-pata-timings.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
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
In drivers/ata/libata-pata-timings.c (ffffffff81bc83a8)
Location: drivers/ata/libata-pata-timings.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
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
In drivers/ata/libata-pata-timings.c (ffffffff81c1ff38)
Location: drivers/ata/libata-pata-timings.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
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
In drivers/ata/libata-pata-timings.c (ffffffff81c750f8)
Location: drivers/ata/libata-pata-timings.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-pata-timings.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffff800010997d4c)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (c0a68938)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (c000000000a5b674)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffe0005f94d6)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff81754048)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff81733ee8)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff81783d58)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
In drivers/ata/libata-core.c (ffffffff8179dc18)
Location: drivers/ata/libata-core.c:3225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_timing_compute
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
