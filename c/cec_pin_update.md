# Function: <code>cec_pin_update</code>

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
void cec_pin_update(struct cec_pin *pin, bool v, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-pin.c (ffff800010ac3f60)
Location: drivers/media/cec/cec-pin.c:111
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
  - drivers/media/cec/cec-pin.c:cec_pin_changed
  - drivers/media/cec/cec-pin.c:cec_pin_low
  - drivers/media/cec/cec-pin.c:cec_pin_read
```
**Symbols:**

```
ffff800010ac3f60-ffff800010ac405c: cec_pin_update (STB_LOCAL)
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
void cec_pin_update(struct cec_pin *pin, bool v, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-pin.c (ffffffff8188b7d0)
Location: drivers/media/cec/cec-pin.c:111
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
  - drivers/media/cec/cec-pin.c:cec_pin_changed
  - drivers/media/cec/cec-pin.c:cec_pin_low
  - drivers/media/cec/cec-pin.c:cec_pin_read
```
**Symbols:**

```
ffffffff8188b7d0-ffffffff8188b879: cec_pin_update (STB_LOCAL)
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
