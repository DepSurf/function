# Function: <code>create_setup_data_node</code>

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
In arch/x86/kernel/ksysfs.c (ffffffff81f674b0)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff81f8f341)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff81fca6d0)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff820aae74)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff826b15fb)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff826dacc1)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff828910a8)
Location: arch/x86/kernel/ksysfs.c:210
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
In arch/x86/kernel/ksysfs.c (ffffffff828a85fd)
Location: arch/x86/kernel/ksysfs.c:209
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
In arch/x86/kernel/ksysfs.c (ffffffff828ab65d)
Location: arch/x86/kernel/ksysfs.c:209
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
int create_setup_data_node(struct kobject *parent, struct kobject **kobjp, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff82cd07f1)
Location: arch/x86/kernel/ksysfs.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
**Symbols:**

```
ffffffff82cd07f1-ffffffff82cd090d: create_setup_data_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_setup_data_node(struct kobject *parent, struct kobject **kobjp, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff82fbc631)
Location: arch/x86/kernel/ksysfs.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
**Symbols:**

```
ffffffff82fbc631-ffffffff82fbc74d: create_setup_data_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff831c6e4c)
Location: arch/x86/kernel/ksysfs.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff832a7d11)
Location: arch/x86/kernel/ksysfs.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff834570b7)
Location: arch/x86/kernel/ksysfs.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff83e75824)
Location: arch/x86/kernel/ksysfs.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff836972f4)
Location: arch/x86/kernel/ksysfs.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff838c7074)
Location: arch/x86/kernel/ksysfs.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
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
In arch/x86/kernel/ksysfs.c (ffffffff8289966f)
Location: arch/x86/kernel/ksysfs.c:209
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
In arch/x86/kernel/ksysfs.c (ffffffff8289192d)
Location: arch/x86/kernel/ksysfs.c:209
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
In arch/x86/kernel/ksysfs.c (ffffffff828ac64f)
Location: arch/x86/kernel/ksysfs.c:209
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
In arch/x86/kernel/ksysfs.c (ffffffff828ac66d)
Location: arch/x86/kernel/ksysfs.c:209
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
</ul>
