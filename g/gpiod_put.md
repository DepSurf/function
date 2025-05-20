# Function: <code>gpiod_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426db0)
Location: drivers/gpio/gpiolib.c:2409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_put_array
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_release
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81426db0-ffffffff81426dc0: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81471f5c)
Location: drivers/gpio/gpiolib.c:3414
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_release
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81471ab0-ffffffff81471ac0: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149407c)
Location: drivers/gpio/gpiolib.c:3535
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_release
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81493d40-ffffffff81493d50: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149d6bc)
Location: drivers/gpio/gpiolib.c:3566
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_release
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff8149d690-ffffffff8149d6a0: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dbcdc)
Location: drivers/gpio/gpiolib.c:3915
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_release
```
**Symbols:**

```
ffffffff814dbcb0-ffffffff814dbcc0: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509f67)
Location: drivers/gpio/gpiolib.c:4192
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_release
```
**Symbols:**

```
ffffffff81509f40-ffffffff81509f50: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151e858)
Location: drivers/gpio/gpiolib.c:4562
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8151e830-ffffffff8151e840: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154ca1f)
Location: drivers/gpio/gpiolib.c:4638
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffff8154c9e0-ffffffff8154c9f6: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156dc0f)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffff8156dbd0-ffffffff8156dbe6: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f5e1)
Location: drivers/gpio/gpiolib.c:5381
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff8160fe20-ffffffff8160fe65: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636041)
Location: drivers/gpio/gpiolib.c:4203
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff81636090-ffffffff816360d5: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816197a1)
Location: drivers/gpio/gpiolib.c:4182
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff8161a1b0-ffffffff8161a1f5: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81688bc1)
Location: drivers/gpio/gpiolib.c:4241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff816895a0-ffffffff816895e5: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5391)
Location: drivers/gpio/gpiolib.c:4365
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff817a6230-ffffffff817a6285: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd5f1)
Location: drivers/gpio/gpiolib.c:4391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff818bdc70-ffffffff818bdcc1: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900271)
Location: drivers/gpio/gpiolib.c:4430
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff819002d0-ffffffff81900315: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947be1)
Location: drivers/gpio/gpiolib.c:4629
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff81948060-ffffffff819480ab: gpiod_put (STB_GLOBAL)
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
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c3608)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffff8000106c35a8-ffff8000106c35d8: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0861a08)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
c08619b4-c08619d8: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083fcac)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
c00000000083fc40-c00000000083fc5c: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a8278)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_ena_gpio_free
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffe0004a8228-ffffffe0004a8254: gpiod_put (STB_GLOBAL)
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
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815633cf)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffff81563390-ffffffff815633a6: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155421f)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffff815541e0-ffffffff815541f6: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561f3f)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffff81561f00-ffffffff81561f16: gpiod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void gpiod_put(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157be2f)
Location: drivers/gpio/gpiolib.c:4903
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_release
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
**Symbols:**

```
ffffffff8157bdf0-ffffffff8157be06: gpiod_put (STB_GLOBAL)
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
