# Function: <code>pm860x_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff8157b2e0)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff8157b2e0-ffffffff8157b30d: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff815d0320)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff815d0320-ffffffff815d035e: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff815fcf30)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff815fcf30-ffffffff815fcf6e: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81610cb0)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff81610cb0-ffffffff81610ce5: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81679530)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff81679530-ffffffff81679565: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff816b5000)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_osc_init
  - drivers/mfd/88pm860x-core.c:device_osc_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff816b5000-ffffffff816b5035: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff816d6260)
Location: drivers/mfd/88pm860x-i2c.c:73
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff816d6260-ffffffff816d6295: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81711a30)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff81711a30-ffffffff81711a65: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81735d30)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff81735d30-ffffffff81735d65: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff817f3330)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff817f3330-ffffffff817f3365: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81806f90)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff81806f90-ffffffff81806fc5: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff817ebbc0)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff817ebbc0-ffffffff817ebbf5: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81878740)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff81878740-ffffffff81878775: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff819c0b20)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff819c0b20-ffffffff819c0b67: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81b36f40)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff81b36f40-ffffffff81b36f87: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81b8a3c0)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff81b8a3c0-ffffffff81b8a407: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81bde2c0)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:device_irq_init
```
**Symbols:**

```
ffffffff81bde2c0-ffffffff81bde307: pm860x_set_bits (STB_GLOBAL)
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
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffff80001092d548)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffff80001092d548-ffff80001092d5b0: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (c0a0bf6c)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
c0a0bf6c-c0a0bfb8: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (c0000000009ccc20)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
c0000000009ccc20-c0000000009cccac: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffe0005a4582)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffe0005a4582-ffffffe0005a45d6: pm860x_set_bits (STB_GLOBAL)
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
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff817291f0)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff817291f0-ffffffff81729225: pm860x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client *i2c, int reg, unsigned char mask, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81744630)
Location: drivers/mfd/88pm860x-i2c.c:70
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_disable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
  - drivers/mfd/88pm860x-core.c:pm8606_osc_enable
```
**Symbols:**

```
ffffffff81744630-ffffffff81744665: pm860x_set_bits (STB_GLOBAL)
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
