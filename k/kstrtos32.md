# Function: <code>kstrtos32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/sysfs.c (ffffffff815532e6)
Location: include/linux/kernel.h:350
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
```
```
In drivers/thermal/thermal_core.c (ffffffff81683cbf)
Location: include/linux/kernel.h:350
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:offset_store
  - drivers/thermal/thermal_core.c:slope_store
  - drivers/thermal/thermal_core.c:integral_cutoff_store
  - drivers/thermal/thermal_core.c:k_d_store
  - drivers/thermal/thermal_core.c:k_i_store
  - drivers/thermal/thermal_core.c:k_pu_store
  - drivers/thermal/thermal_core.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/sysfs.c (ffffffff815a52d6)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
```
```
In drivers/thermal/thermal_core.c (ffffffff816e531f)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:offset_store
  - drivers/thermal/thermal_core.c:slope_store
  - drivers/thermal/thermal_core.c:integral_cutoff_store
  - drivers/thermal/thermal_core.c:k_d_store
  - drivers/thermal/thermal_core.c:k_i_store
  - drivers/thermal/thermal_core.c:k_pu_store
  - drivers/thermal/thermal_core.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/sysfs.c (ffffffff815d3a86)
Location: include/linux/kernel.h:359
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81718e5f)
Location: include/linux/kernel.h:359
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814173e6)
Location: include/linux/kernel.h:372
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff815e8606)
Location: include/linux/kernel.h:372
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817310ff)
Location: include/linux/kernel.h:372
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81441e26)
Location: include/linux/kernel.h:409
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff8164f986)
Location: include/linux/kernel.h:409
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817a218f)
Location: include/linux/kernel.h:409
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81474c80)
Location: include/linux/kernel.h:425
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff8168b403)
Location: include/linux/kernel.h:425
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817e97fb)
Location: include/linux/kernel.h:425
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814926a0)
Location: include/linux/kernel.h:458
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816ab633)
Location: include/linux/kernel.h:458
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff818156ab)
Location: include/linux/kernel.h:458
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814bfb11)
Location: include/linux/kernel.h:417
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816e51d3)
Location: include/linux/kernel.h:417
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff818578cb)
Location: include/linux/kernel.h:417
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d8961)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817094b3)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8188937b)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815384ad)
Location: include/linux/kernel.h:410
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817c4503)
Location: include/linux/kernel.h:410
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81957d7b)
Location: include/linux/kernel.h:410
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8155530d)
Location: include/linux/kernel.h:262
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817d8fe3)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195d3db)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8155dc7a)
Location: include/linux/kernel.h:272
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817bd3b3)
Location: include/linux/kernel.h:272
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8194062b)
Location: include/linux/kernel.h:272
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815bef8a)
Location: include/linux/kstrtox.h:89
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff81847733)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e4f4b)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81668b12)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
```
```
In drivers/base/power/sysfs.c (ffffffff8198c25a)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4a262)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81723302)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
```
```
In drivers/base/power/sysfs.c (ffffffff81afbd4a)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce1ad2)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8175f742)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a13a)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d49d72)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817a0f32)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
```
```
In drivers/base/power/sysfs.c (ffffffff81ba252a)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e00b82)
Location: include/linux/kstrtox.h:89
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffff8000105d4bcc)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffff8000108f72dc)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad6bf8)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (c0782504)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (c09e3268)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7288)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (c000000000762d48)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (c000000000992a38)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbd164)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffe000418f64)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffe000587fe6)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d1c8c)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d0f41)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816cec03)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182f1fb)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c1961)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816a9f33)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f688b)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814ccfd1)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816fd173)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187e82b)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814e5aa1)
Location: include/linux/kernel.h:421
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff81717a03)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189a2ab)
Location: include/linux/kernel.h:421
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
```
</details>
</li>
</ul>

## Differences
