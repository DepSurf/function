# Function: <code>pinconf_to_config_argument</code>

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
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8142222b)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
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
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146a986)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146b5e2)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
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
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489c96)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148abd3)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148b9e4)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148d823)
Location: include/linux/pinctrl/pinconf-generic.h:147
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81492a41)
Location: include/linux/pinctrl/pinconf-generic.h:139
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8149376b)
Location: include/linux/pinctrl/pinconf-generic.h:139
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814944b3)
Location: include/linux/pinctrl/pinconf-generic.h:139
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8149531a)
Location: include/linux/pinctrl/pinconf-generic.h:139
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81497225)
Location: include/linux/pinctrl/pinconf-generic.h:139
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff814cecd1)
Location: include/linux/pinctrl/pinconf-generic.h:146
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cf9fb)
Location: include/linux/pinctrl/pinconf-generic.h:146
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0853)
Location: include/linux/pinctrl/pinconf-generic.h:146
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d161a)
Location: include/linux/pinctrl/pinconf-generic.h:146
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d3545)
Location: include/linux/pinctrl/pinconf-generic.h:146
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5840)
Location: include/linux/pinctrl/pinconf-generic.h:146
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff814ffcf5)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500be9)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81502065)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815026ff)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815045f3)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81514765)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815156b9)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81516b55)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8151720f)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81519113)
Location: include/linux/pinctrl/pinconf-generic.h:148
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81542939)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543882)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81544cf5)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81545341)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815472c0)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff815637c9)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564792)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81565bd5)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8156628b)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815681e0)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81605d22)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606cae)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160831a)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81609fdb)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160b580)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8162a4f2)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b57e)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162cb1a)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162e6eb)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162fc74)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632bae)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8160e1d2)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f24b)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff816107fd)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8161225b)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81613914)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816168b5)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8167cf57)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e18c)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167f8d1)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8168145b)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682a74)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81685b25)
Location: include/linux/pinctrl/pinconf-generic.h:158
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff817988d7)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799d74)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179b5eb)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179d5b8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179faa8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a23c9)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff818ae7c7)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818afedc)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b1e4b)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b416d)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b67c8)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b9634)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff818f1717)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2cac)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f4e77)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f71e3)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f9884)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fc88b)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81938ec7)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193a4dc)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193c687)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193e9a8)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81940c54)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943988)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffff80001069136c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693ee4)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694af8)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_set
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (ffff800010695b38)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffff800010696a10)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069a848)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069c12c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069eb64)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a0698)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3460)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2711_pinconf_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinconf_set
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a604c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a6b6c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a8a38)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ae210)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b1350)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b3154)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b4f0c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b84b4)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba548)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc770)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106cedb4)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
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
In drivers/pinctrl/pinconf-generic.c (c0832f58)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (c0835124)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (c08360ac)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set
```
```
In drivers/pinctrl/pinctrl-palmas.c (c0836c98)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c0839290)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083d2cc)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set
```
```
In drivers/pinctrl/pinctrl-single.c (c083ed7c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c084137c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0846234)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
```
```
In drivers/pinctrl/aspeed/pinctrl-aspeed.c (c08472dc)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_set
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c084916c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084c734)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084e53c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (c0853fa0)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c085713c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c08593a0)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b234)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868768)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
```
```
In drivers/gpio/gpio-omap.c (c086e008)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_set_config
```
```
In drivers/gpio/gpio-tegra.c (c0870ff4)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set_config
```
```
In drivers/soc/tegra/pmc.c (c093c404)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
```
```
In drivers/rtc/rtc-omap.c (c0b8c518)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:rtc_pinconf_set
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
In drivers/pinctrl/pinconf-generic.c (c00000000082d380)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082fcb8)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-palmas.c (c00000000083195c)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833444)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c000000000836bf4)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/gpio/gpio-ftgpio010.c (c00000000084a344)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
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
In drivers/pinctrl/pinconf-generic.c (ffffffe00049cb0a)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e920)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049f420)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a07fc)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a28b8)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae7d8)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8155bdb9)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155cd82)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155d75b)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8154c279)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154c89b)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154e7f0)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81557af9)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558ac2)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559f05)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155a5bb)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155c510)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81571989)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572952)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573d95)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8157444b)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815763a0)
Location: include/linux/pinctrl/pinconf-generic.h:156
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
</details>
</li>
</ul>

## Differences
