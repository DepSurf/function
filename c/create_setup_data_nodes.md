# Function: <code>create_setup_data_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81f673e1)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81f8f27f)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81fca60e)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff820aadb8)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff826b153a)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff826dabf3)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff82890fd5)
Location: arch/x86/kernel/ksysfs.c:266
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff828a8542)
Location: arch/x86/kernel/ksysfs.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff828ab5a2)
Location: arch/x86/kernel/ksysfs.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff82cd090d)
Location: arch/x86/kernel/ksysfs.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff82cd090d-ffffffff82cd0a47: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff82fbc74d)
Location: arch/x86/kernel/ksysfs.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff82fbc74d-ffffffff82fbc887: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff831c6d6b)
Location: arch/x86/kernel/ksysfs.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff831c6d6b-ffffffff831c6f9d: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff832a7c30)
Location: arch/x86/kernel/ksysfs.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff832a7c30-ffffffff832a7e95: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff83456fdd)
Location: arch/x86/kernel/ksysfs.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff83456fdd-ffffffff83457258: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff83e75720)
Location: arch/x86/kernel/ksysfs.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff83e75720-ffffffff83e759b0: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff836971f0)
Location: arch/x86/kernel/ksysfs.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff836971f0-ffffffff83697480: create_setup_data_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_setup_data_nodes(struct kobject *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff838c6f70)
Location: arch/x86/kernel/ksysfs.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
**Symbols:**

```
ffffffff838c6f70-ffffffff838c7200: create_setup_data_nodes (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff828995b4)
Location: arch/x86/kernel/ksysfs.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff82891872)
Location: arch/x86/kernel/ksysfs.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff828ac594)
Location: arch/x86/kernel/ksysfs.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff828ac5b2)
Location: arch/x86/kernel/ksysfs.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
