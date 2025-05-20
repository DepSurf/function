# Function: <code>psp_acquire_i2c_bus</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int psp_acquire_i2c_bus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-amdpsp.c (0)
Location: drivers/i2c/busses/i2c-designware-amdpsp.c:243
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_trylock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_lock_bus
```
**Symbols:**

```
ffffffff81b3a4a0-ffffffff81b3a51c: psp_acquire_i2c_bus (STB_LOCAL)
ffffffff81ef1ccc-ffffffff81ef1ce0: psp_acquire_i2c_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int psp_acquire_i2c_bus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-amdpsp.c (0)
Location: drivers/i2c/busses/i2c-designware-amdpsp.c:281
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_trylock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_lock_bus
```
**Symbols:**

```
ffffffff81ccff40-ffffffff81ccffd4: psp_acquire_i2c_bus (STB_LOCAL)
ffffffff820a7747-ffffffff820a775b: psp_acquire_i2c_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
