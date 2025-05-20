# Function: <code>i2c_verify_client</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81677ee5)
Location: drivers/i2c/i2c-core.c:845
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_device_shutdown
  - drivers/i2c/i2c-core.c:i2c_cmd
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_match
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
```
**Symbols:**

```
ffffffff81677f20-ffffffff81677f40: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816d8885)
Location: drivers/i2c/i2c-core.c:978
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_cmd
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
  - drivers/i2c/i2c-core.c:i2c_device_shutdown
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_match
```
**Symbols:**

```
ffffffff816d87c0-ffffffff816d87e0: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81708985)
Location: drivers/i2c/i2c-core.c:1115
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_cmd
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
  - drivers/i2c/i2c-core.c:i2c_device_shutdown
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_match
```
**Symbols:**

```
ffffffff817088c0-ffffffff817088e0: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171f8ec)
Location: drivers/i2c/i2c-core-base.c:517
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8171e510-ffffffff8171e52d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8179084c)
Location: drivers/i2c/i2c-core-base.c:522
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8178f7b0-ffffffff8178f7cd: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d2135)
Location: drivers/i2c/i2c-core-base.c:503
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff817d20d0-ffffffff817d20ed: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817f9295)
Location: drivers/i2c/i2c-core-base.c:515
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff817f9230-ffffffff817f924d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81839fa5)
Location: drivers/i2c/i2c-core-base.c:513
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81839f40-ffffffff81839f5d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186b915)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8186b8b0-ffffffff8186b8cd: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8193f615)
Location: drivers/i2c/i2c-core-base.c:528
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff8193f5b0-ffffffff8193f5cd: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819457c5)
Location: drivers/i2c/i2c-core-base.c:656
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81945760-ffffffff8194577d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81928f95)
Location: drivers/i2c/i2c-core-base.c:700
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81928f30-ffffffff81928f4d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cc0e5)
Location: drivers/i2c/i2c-core-base.c:701
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff819cc080-ffffffff819cc09d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2d915)
Location: drivers/i2c/i2c-core-base.c:702
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81b2d870-ffffffff81b2d899: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc1a65)
Location: drivers/i2c/i2c-core-base.c:703
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81cc19b0-ffffffff81cc19d9: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d29475)
Location: drivers/i2c/i2c-core-base.c:718
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81d293c0-ffffffff81d293e9: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81ddf335)
Location: drivers/i2c/i2c-core-base.c:721
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81ddf280-ffffffff81ddf2a9: i2c_verify_client (STB_GLOBAL)
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
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aae7bc)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
**Symbols:**

```
ffff800010aae6e0-ffff800010aae71c: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b900f0)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
**Symbols:**

```
c0b90044-c0b90074: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b90930)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
**Symbols:**

```
c000000000b90880-c000000000b908b8: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b6ce6)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
**Symbols:**

```
ffffffe0006b6c2c-ffffffe0006b6c60: i2c_verify_client (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8185faa5)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8185fa40-ffffffff8185fa5d: i2c_verify_client (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_verify_client(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187acb5)
Location: drivers/i2c/i2c-core-base.c:518
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_cmd
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8187ac50-ffffffff8187ac6d: i2c_verify_client (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
