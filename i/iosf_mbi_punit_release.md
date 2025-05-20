# Function: <code>iosf_mbi_punit_release</code>

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
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107e600)
Location: arch/x86/platform/intel/iosf_mbi.c:201
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff8107e600-ffffffff8107e617: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81084e30)
Location: arch/x86/platform/intel/iosf_mbi.c:201
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff81084e30-ffffffff81084e47: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088130)
Location: arch/x86/platform/intel/iosf_mbi.c:201
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff81088130-ffffffff81088147: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108f890)
Location: arch/x86/platform/intel/iosf_mbi.c:227
Inline: False
```
**Symbols:**

```
ffffffff8108f890-ffffffff8108f8a7: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093560)
Location: arch/x86/platform/intel/iosf_mbi.c:218
Inline: False
```
**Symbols:**

```
ffffffff81093560-ffffffff81093577: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810947a0)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810947a0-ffffffff810947f3: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099b97)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81099a60-ffffffff81099ab9: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098c87)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81098b50-ffffffff81098ba9: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810994c7)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81099390-ffffffff810993e9: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a9497)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810a9380-ffffffff810a93d9: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810bed17)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810bebc0-ffffffff810bec35: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810da937)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810da7c0-ffffffff810da835: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e5ec7)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810e5d50-ffffffff810e5dc5: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee2b7)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810ee140-ffffffff810ee1b5: iosf_mbi_punit_release (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093760)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81093760-ffffffff810937b3: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810821f0)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810821f0-ffffffff81082243: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093710)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81093710-ffffffff81093763: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_punit_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095c60)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81095c60-ffffffff81095cb3: iosf_mbi_punit_release (STB_GLOBAL)
```
</details>
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
