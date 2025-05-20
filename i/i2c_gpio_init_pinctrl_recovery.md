# Function: <code>i2c_gpio_init_pinctrl_recovery</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:259
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81946840-ffffffff81946976: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
ffffffff81c24756-ffffffff81c2476a: i2c_gpio_init_pinctrl_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:281
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff8192a070-ffffffff8192a1a6: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
ffffffff81c16813-ffffffff81c16827: i2c_gpio_init_pinctrl_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:281
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff819cd1f0-ffffffff819cd31d: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
ffffffff81d254fe-ffffffff81d25512: i2c_gpio_init_pinctrl_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:281
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81b2f2d0-ffffffff81b2f419: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
ffffffff81ef13b9-ffffffff81ef13cd: i2c_gpio_init_pinctrl_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc3190)
Location: drivers/i2c/i2c-core-base.c:281
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81cc3190-ffffffff81cc32cc: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2acb0)
Location: drivers/i2c/i2c-core-base.c:301
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81d2acb0-ffffffff81d2ae1c: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void i2c_gpio_init_pinctrl_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de0b70)
Location: drivers/i2c/i2c-core-base.c:304
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81de0b70-ffffffff81de0cdc: i2c_gpio_init_pinctrl_recovery (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
