# Function: <code>cec_pin_start_timer</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_pin_start_timer(struct cec_pin *pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-pin.c (ffff800010ac428c)
Location: drivers/media/cec/cec-pin.c:1155
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_transmit
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_transmit
```
**Symbols:**

```
ffff800010ac41b8-ffff800010ac421c: cec_pin_start_timer.part.0 (STB_LOCAL)
ffff800010ac5390-ffff800010ac53c8: cec_pin_start_timer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cec_pin_start_timer(struct cec_pin *pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-pin.c (ffffffff8188c640)
Location: drivers/media/cec/cec-pin.c:1155
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_transmit
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_transmit
```
**Symbols:**

```
ffffffff8188c550-ffffffff8188c5ac: cec_pin_start_timer.part.0 (STB_LOCAL)
ffffffff8188d120-ffffffff8188d13a: cec_pin_start_timer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
