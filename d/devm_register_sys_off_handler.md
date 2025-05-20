# Function: <code>devm_register_sys_off_handler</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devm_register_sys_off_handler(struct device *dev, enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102b46)
Location: kernel/reboot.c:485
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81102ab0-ffffffff81102b2b: devm_register_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devm_register_sys_off_handler(struct device *dev, enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81128056)
Location: kernel/reboot.c:502
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81127f20-ffffffff81127f9b: devm_register_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devm_register_sys_off_handler(struct device *dev, enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81135506)
Location: kernel/reboot.c:502
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff811353c0-ffffffff81135442: devm_register_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int devm_register_sys_off_handler(struct device *dev, enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140556)
Location: kernel/reboot.c:516
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81140330-ffffffff811403b6: devm_register_sys_off_handler (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
