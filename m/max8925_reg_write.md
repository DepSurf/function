# Function: <code>max8925_reg_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81590530)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff81590530-ffffffff815905bd: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff815e53a0)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff815e53a0-ffffffff815e542d: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81612250)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81612250-ffffffff816122dd: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff816262c0)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff816262c0-ffffffff8162634d: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff8168eb90)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff8168eb90-ffffffff8168ec1d: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff816cac80)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff816cac80-ffffffff816cad0f: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff816ec200)
Location: drivers/mfd/max8925-i2c.c:69
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff816ec200-ffffffff816ec28f: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81725960)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81725960-ffffffff817259ed: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81749c20)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81749c20-ffffffff81749cad: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81807aa0)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81807aa0-ffffffff81807b2b: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81817ae0)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81817ae0-ffffffff81817b6b: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff817fbf50)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff817fbf50-ffffffff817fbfd8: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81885500)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81885500-ffffffff81885588: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff819ce280)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff819ce280-ffffffff819ce322: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81b46ee0)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81b46ee0-ffffffff81b46f82: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81b9a2b0)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81b9a2b0-ffffffff81b9a352: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81bee260)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81bee260-ffffffff81bee302: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffff800010947758)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffff800010947758-ffff8000109477f8: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (c0a30a14)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
c0a30a14-c0a30aac: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (c0000000009f2490)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
c0000000009f2490-c0000000009f2564: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffe0005b98e2)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffe0005b98e2-ffffffe0005b9956: max8925_reg_write (STB_GLOBAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff8173d0e0)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff8173d0e0-ffffffff8173d16d: max8925_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int max8925_reg_write(struct i2c_client *i2c, int reg, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8925-i2c.c (ffffffff81758520)
Location: drivers/mfd/max8925-i2c.c:66
Inline: False
Direct callers:
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
  - drivers/mfd/max8925-core.c:max8925_irq_sync_unlock
```
**Symbols:**

```
ffffffff81758520-ffffffff817585ad: max8925_reg_write (STB_GLOBAL)
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
