# Function: <code>iosf_mbi_call_pmic_bus_access_notifier_chain</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iosf_mbi_call_pmic_bus_access_notifier_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107e6a0)
Location: arch/x86/platform/intel/iosf_mbi.c:235
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff8107e6a0-ffffffff8107e6bd: iosf_mbi_call_pmic_bus_access_notifier_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iosf_mbi_call_pmic_bus_access_notifier_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81084ed0)
Location: arch/x86/platform/intel/iosf_mbi.c:235
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff81084ed0-ffffffff81084eed: iosf_mbi_call_pmic_bus_access_notifier_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iosf_mbi_call_pmic_bus_access_notifier_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088190)
Location: arch/x86/platform/intel/iosf_mbi.c:244
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff81088190-ffffffff810881ad: iosf_mbi_call_pmic_bus_access_notifier_chain (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
