# Function: <code>devres_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815500d0)
Location: drivers/base/devres.c:363
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/phy/phy-core.c:devm_phy_put
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff815500d0-ffffffff815500f4: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1ed0)
Location: drivers/base/devres.c:363
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff815a1ed0-ffffffff815a1ef4: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d05f0)
Location: drivers/base/devres.c:364
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff815d05f0-ffffffff815d0614: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4cb0)
Location: drivers/base/devres.c:364
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff815e4cb0-ffffffff815e4cd4: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164bf80)
Location: drivers/base/devres.c:364
Inline: True
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff8164bf80-ffffffff8164bfa4: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816875a0)
Location: drivers/base/devres.c:368
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff816875a0-ffffffff816875c4: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a75f0)
Location: drivers/base/devres.c:376
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_free_irq
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff816a75f0-ffffffff816a7614: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816e06f0)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff816e06f0-ffffffff816e0716: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704910)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81704910-ffffffff81704936: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817bea70)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff817bea70-ffffffff817beaa2: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3940)
Location: drivers/base/devres.c:392
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff817d3940-ffffffff817d3972: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7350)
Location: drivers/base/devres.c:392
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff817b7350-ffffffff817b7382: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840de9)
Location: drivers/base/devres.c:385
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_remove_action
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81840d40-ffffffff81840d72: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81984139)
Location: drivers/base/devres.c:385
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_remove_action
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81984070-ffffffff819840ba: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af2239)
Location: drivers/base/devres.c:390
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_remove_action
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81af2150-ffffffff81af219a: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b403e9)
Location: drivers/base/devres.c:390
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_remove_action
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81b40300-ffffffff81b4034a: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b98289)
Location: drivers/base/devres.c:390
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_remove_action
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81b981a0-ffffffff81b981ea: devres_destroy (STB_GLOBAL)
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
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f06c0)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffff8000108f06c0-ffff8000108f072c: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dda70)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
  - sound/soc/soc-jack.c:snd_soc_jack_free_gpios
```
**Symbols:**

```
c09dda70-c09ddaa4: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989b20)
Location: drivers/base/devres.c:376
Inline: False
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_remove_action
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
c000000000989b20-c000000000989b74: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582c70)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffe000582c70-ffffffe000582cd0: devres_destroy (STB_GLOBAL)
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
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca060)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff816ca060-ffffffff816ca086: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a5390)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff816a5390-ffffffff816a53b6: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f85d0)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff816f85d0-ffffffff816f85f6: devres_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devres_destroy(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712e70)
Location: drivers/base/devres.c:376
Inline: True
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/irq/devres.c:devm_free_irq
  - kernel/dma/mapping.c:dmam_free_coherent
  - lib/devres.c:devm_ioport_unmap
  - lib/devres.c:devm_iounmap
  - drivers/input/input.c:input_free_device
```
**Symbols:**

```
ffffffff81712e70-ffffffff81712e96: devres_destroy (STB_GLOBAL)
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
