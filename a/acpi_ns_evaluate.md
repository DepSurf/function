# Function: <code>acpi_ns_evaluate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff8149cae7)
Location: drivers/acpi/acpica/nseval.c:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff8149cae7-ffffffff8149cd2e: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff814ebc84)
Location: drivers/acpi/acpica/nseval.c:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff814ebc84-ffffffff814ebed6: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff8150e50a)
Location: drivers/acpi/acpica/nseval.c:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff8150e50a-ffffffff8150e75c: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff8151ebc1)
Location: drivers/acpi/acpica/nseval.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff8151ebc1-ffffffff8151ee13: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81570e80)
Location: drivers/acpi/acpica/nseval.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81570e80-ffffffff815712b5: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff815a7b78)
Location: drivers/acpi/acpica/nseval.c:48
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff815a7b78-ffffffff815a7fbd: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff815c0963)
Location: drivers/acpi/acpica/nseval.c:48
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff815c0963-ffffffff815c0e50: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff815f25d1)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff815f25d1-ffffffff815f2abf: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81613a6d)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81613a6d-ffffffff81613f5d: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff816bff83)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff816bff83-ffffffff816c0473: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff816ddafc)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff816ddafc-ffffffff816ddfec: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff816bf9e8)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff816bf9e8-ffffffff816bfed8: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81736c9d)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81736c9d-ffffffff8173718d: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81867f03)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81867f03-ffffffff81868418: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff819a68d0)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff819a68d0-ffffffff819a6eb7: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff819ed5f0)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff819ed5f0-ffffffff819edbdb: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81a383b0)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81a383b0-ffffffff81a3899b: acpi_ns_evaluate (STB_GLOBAL)
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffff80001078cddc)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffff80001078cddc-ffff80001078d04c: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff815f3019)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff815f3019-ffffffff815f3280: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff815de5a7)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff815de5a7-ffffffff815de80e: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81607d4d)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81607d4d-ffffffff8160823d: acpi_ns_evaluate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nseval.c (ffffffff81621bfd)
Location: drivers/acpi/acpica/nseval.c:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81621bfd-ffffffff816220ed: acpi_ns_evaluate (STB_GLOBAL)
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
