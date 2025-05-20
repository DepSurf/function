# Function: <code>irq_free_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da050)
Location: kernel/irq/irqdesc.c:403
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff810da050-ffffffff810da0c2: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df540)
Location: kernel/irq/irqdesc.c:461
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff810df540-ffffffff810df5b2: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5c80)
Location: kernel/irq/irqdesc.c:649
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff810e5c80-ffffffff810e5cf2: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e52a0)
Location: kernel/irq/irqdesc.c:666
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff810e52a0-ffffffff810e5313: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ed500)
Location: kernel/irq/irqdesc.c:659
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff810ed500-ffffffff810ed57e: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f58d0)
Location: kernel/irq/irqdesc.c:676
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff810f58d0-ffffffff810f594d: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81101060)
Location: kernel/irq/irqdesc.c:681
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81101060-ffffffff811010dd: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109860)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81109860-ffffffff811098dd: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81115c30)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81115c30-ffffffff81115cad: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121730)
Location: kernel/irq/irqdesc.c:742
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81121730-ffffffff811217ad: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111d860)
Location: kernel/irq/irqdesc.c:744
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff8111d860-ffffffff8111d8dd: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111da20)
Location: kernel/irq/irqdesc.c:744
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff8111da20-ffffffff8111da9d: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113de30)
Location: kernel/irq/irqdesc.c:756
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff8113de30-ffffffff8113dead: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161400)
Location: kernel/irq/irqdesc.c:733
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81161400-ffffffff811614a5: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81194960)
Location: kernel/irq/irqdesc.c:760
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81194960-ffffffff81194a05: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6220)
Location: kernel/irq/irqdesc.c:781
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff811a6220-ffffffff811a629f: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b5d10)
Location: kernel/irq/irqdesc.c:781
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:xen_allocate_irq_dynamic
  - drivers/xen/events/events_base.c:delayed_free_irq
```
**Symbols:**

```
ffffffff811b5d10-ffffffff811b5d8f: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff8000101773a8)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffff8000101773a8-ffff800010177458: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c92dc)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_cleanup
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
**Symbols:**

```
c03c92dc-c03c9364: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d0ef0)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
**Symbols:**

```
c0000000001d0ef0-c0000000001d0ff0: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe0001123fa)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
**Symbols:**

```
ffffffe0001123fa-ffffffe000112496: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e210)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff8110e210-ffffffff8110e28d: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810fef70)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irq_sim.c:irq_sim_fini
  - kernel/irq/irq_sim.c:irq_sim_init
```
**Symbols:**

```
ffffffff810fef70-ffffffff810fefed: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c100)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff8110c100-ffffffff8110c17d: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117830)
Location: kernel/irq/irqdesc.c:736
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_irq_desc_release
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - drivers/xen/events/events_base.c:xen_free_irq
```
**Symbols:**

```
ffffffff81117830-ffffffff811178ad: irq_free_descs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
