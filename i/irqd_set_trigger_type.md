# Function: <code>irqd_set_trigger_type</code>

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
In drivers/base/platform.c (ffffffff8154d886)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
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
In kernel/irq/irqdomain.c (ffffffff810e70c1)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff8159f688)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
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
In kernel/irq/irqdomain.c (ffffffff810edab1)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff815cdcc4)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
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
In kernel/irq/irqdomain.c (ffffffff810ed4d7)
Location: include/linux/irq.h:270
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff815e26db)
Location: include/linux/irq.h:270
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81720cfe)
Location: include/linux/irq.h:270
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In kernel/irq/manage.c (ffffffff810f0159)
Location: include/linux/irq.h:281
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff810f5eda)
Location: include/linux/irq.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff81649884)
Location: include/linux/irq.h:281
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8179207f)
Location: include/linux/irq.h:281
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In kernel/irq/manage.c (ffffffff810f8581)
Location: include/linux/irq.h:276
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff810fe22d)
Location: include/linux/irq.h:276
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff81684e4c)
Location: include/linux/irq.h:276
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d4aa2)
Location: include/linux/irq.h:276
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In kernel/irq/manage.c (ffffffff81103d21)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811099fd)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff816a4a9c)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fbc15)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In kernel/irq/manage.c (ffffffff8110c7a3)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81112fec)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff816dda64)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c97a)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff81118b83)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8111f27d)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff81701b16)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186e37a)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff81124762)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8112b7bd)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff817bc956)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81942160)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff811205c9)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8112727d)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff817d1858)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819484af)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff8112089f)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8112753d)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff817b5288)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192be10)
Location: include/linux/irq.h:291
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff81140e13)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81147aa9)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff8183e578)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cefd0)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff81164759)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8116bfeb)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In kernel/irq/irq_sim.c (ffffffff8116c24e)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_type
```
```
In drivers/base/platform.c (ffffffff81981357)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30d6c)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff8119857d)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811a0835)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In kernel/irq/irq_sim.c (ffffffff811a11ce)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_type
```
```
In drivers/base/platform.c (ffffffff81aeeea7)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc56dc)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff811aa280)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811b26a7)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In kernel/irq/irq_sim.c (ffffffff811b2fde)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_type
```
```
In drivers/base/platform.c (ffffffff81b3d297)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d36c)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff811b9d69)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811c2497)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In kernel/irq/irq_sim.c (ffffffff811c2dfe)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_type
```
```
In drivers/base/platform.c (ffffffff81b94de2)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de325c)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffff80001017b634)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffff800010184ddc)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001066b54c)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
```
```
In drivers/base/platform.c (ffff8000108edc8c)
Location: include/linux/irq.h:280
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab1a34)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (c03cc524)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (c03d3e9c)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (c09dbba4)
Location: include/linux/irq.h:280
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c0b93150)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In arch/powerpc/sysdev/mpic.c (c0000000000b5330)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
```
```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba8c0)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_set_irq_type
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bcc54)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_type
```
```
In kernel/irq/manage.c (c0000000001d5c8c)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (c0000000001df2f4)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (c000000000986234)
Location: include/linux/irq.h:280
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c000000000b94f04)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffe0001150c4)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffe00011bc32)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffe000580e8a)
Location: include/linux/irq.h:280
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9842)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff81111163)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8111785d)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff816c7266)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
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
In kernel/irq/manage.c (ffffffff81101e93)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8110854d)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In kernel/irq/irq_sim.c (ffffffff811088b1)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_type
```
```
In drivers/base/platform.c (ffffffff816a2566)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
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
In kernel/irq/manage.c (ffffffff8110f053)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8111574d)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff816f57d6)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186250a)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/irq/manage.c (ffffffff8111a583)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81120d7d)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/base/platform.c (ffffffff81710066)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d76a)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
```
</details>
</li>
</ul>

## Differences
