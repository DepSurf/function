# Function: <code>rc5t583_write</code>

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
In drivers/mfd/rc5t583.c (ffffffff81594fdb)
Location: include/linux/mfd/rc5t583.h:337
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff815955e0)
Location: include/linux/mfd/rc5t583.h:337
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In drivers/mfd/rc5t583.c (ffffffff815ea00c)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff815ea751)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff81616e1c)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81617561)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8162ad1c)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8162b441)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8169365c)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81693d81)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff816cf785)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816cfed1)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff816f0da5)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816f14f1)
Location: include/linux/mfd/rc5t583.h:338
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8172a405)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8172aac0)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8174e605)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8174ecc0)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8180caf2)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8180d370)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8181bc02)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8181c300)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff817ff0e9)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff817ff6c0)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff81888ef7)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81889dbd)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff819d2197)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff819d306c)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff81b4c2a7)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81b4d418)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff81b9f6f7)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81ba0888)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff81bf3857)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81bf49e8)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffff80001094d5b0)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffff80001094ddd4)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (c0a373e4)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (c0a37e48)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (c0000000009f9ab8)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (c0000000009fa4e0)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffe0005be6dc)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffe0005bedca)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583.c (ffffffff81741ac5)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81742180)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
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
In drivers/mfd/rc5t583.c (ffffffff8175cf05)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8175d5c0)
Location: include/linux/mfd/rc5t583.h:326
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
</details>
</li>
</ul>

## Differences
