# Function: <code>cec_pin_to_idle</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void cec_pin_to_idle(struct cec_pin *pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-pin.c (ffff800010ac3c30)
Location: drivers/media/cec/cec-pin.c:323
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_tx_states
  - drivers/media/cec/cec-pin.c:cec_pin_tx_states
  - drivers/media/cec/cec-pin.c:cec_pin_tx_states
```
**Symbols:**

```
ffff800010ac3c30-ffff800010ac3cbc: cec_pin_to_idle (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_pin_to_idle(struct cec_pin *pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-pin.c (ffffffff8188b960)
Location: drivers/media/cec/cec-pin.c:323
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_tx_states
  - drivers/media/cec/cec-pin.c:cec_pin_tx_states
  - drivers/media/cec/cec-pin.c:cec_pin_tx_states
```
**Symbols:**

```
ffffffff8188b960-ffffffff8188b9ea: cec_pin_to_idle (STB_LOCAL)
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
