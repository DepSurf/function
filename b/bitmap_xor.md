# Function: <code>bitmap_xor</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f291)
Location: include/linux/bitmap.h:280
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In mm/sparse.c (ffffffff8128dad2)
Location: include/linux/bitmap.h:280
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8154d436)
Location: include/linux/bitmap.h:280
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In mm/sparse.c (ffffffff8129d715)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8156e63a)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In mm/sparse.c (ffffffff812d1316)
Location: include/linux/bitmap.h:300
Inline: True
Inline callers:
  - mm/sparse.c:clear_subsection_map
```
```
In drivers/gpio/gpiolib.c (ffffffff81612af6)
Location: include/linux/bitmap.h:300
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81a8a1e3)
Location: include/linux/bitmap.h:300
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In mm/sparse.c (ffffffff812dce36)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/sparse.c:clear_subsection_map
```
```
In drivers/gpio/gpiolib.c (ffffffff81637b84)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81a93a6a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In mm/sparse.c (ffffffff812e46e9)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8161b511)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81a7d4a2)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In mm/sparse.c (ffffffff8132b9f9)
Location: include/linux/bitmap.h:304
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8168aa3b)
Location: include/linux/bitmap.h:304
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81b376a4)
Location: include/linux/bitmap.h:304
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In mm/sparse.c (ffffffff8139b697)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff817a7caf)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81cc30fc)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In mm/sparse.c (ffffffff8141b6d7)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff818c02a3)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81e823fc)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In kernel/bpf/cpumask.c (ffffffff8135d9b5)
Location: include/linux/bitmap.h:335
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_xor
```
```
In mm/sparse.c (ffffffff8144ec77)
Location: include/linux/bitmap.h:335
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff81903281)
Location: include/linux/bitmap.h:335
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81edea40)
Location: include/linux/bitmap.h:335
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In kernel/bpf/cpumask.c (ffffffff81386755)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_xor
```
```
In mm/sparse.c (ffffffff8148881b)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8194ae17)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In net/ethtool/features.c (ffffffff81fa2872)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In mm/sparse.c (ffff80001033c86c)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffff8000106c40b4)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In drivers/gpio/gpiolib.c (c086250c)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9ffc)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In mm/sparse.c (c0000000004178e8)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (c000000000840888)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In drivers/gpio/gpiolib.c (ffffffe0004a8b0e)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In mm/sparse.c (ffffffff81295cf5)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff81563dfa)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In mm/sparse.c (ffffffff81287905)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff81554c4a)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852a8a)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
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
In mm/sparse.c (ffffffff81293b05)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8156296a)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In mm/sparse.c (ffffffff812a3965)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/gpio/gpiolib.c (ffffffff8157c883)
Location: include/linux/bitmap.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
</details>
</li>
</ul>

## Differences
