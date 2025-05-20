# Function: <code>smp_read_mpc</code>

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
In arch/x86/kernel/mpparse.c (ffffffff81f70d2f)
Location: arch/x86/kernel/mpparse.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff81f99461)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff81fd4937)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff820b55f5)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff826bbdcc)
Location: arch/x86/kernel/mpparse.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff826e5b91)
Location: arch/x86/kernel/mpparse.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff8289c6cc)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff828b44a4)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff828b78fb)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smp_read_mpc(struct mpc_table *mpc, unsigned int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82cdc2f6)
Location: arch/x86/kernel/mpparse.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff82cdc2f6-ffffffff82cdc45c: smp_read_mpc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82fc8df0)
Location: arch/x86/kernel/mpparse.c:192
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff831d3732)
Location: arch/x86/kernel/mpparse.c:192
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff832b6296)
Location: arch/x86/kernel/mpparse.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff83467cc4)
Location: arch/x86/kernel/mpparse.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff83e8bbfa)
Location: arch/x86/kernel/mpparse.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:check_physptr
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
In arch/x86/kernel/mpparse.c (ffffffff836af424)
Location: arch/x86/kernel/mpparse.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:check_physptr
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
In arch/x86/kernel/mpparse.c (ffffffff838df994)
Location: arch/x86/kernel/mpparse.c:188
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:check_physptr
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
In arch/x86/kernel/mpparse.c (ffffffff828a5902)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff8289da44)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff828b8812)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
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
In arch/x86/kernel/mpparse.c (ffffffff828b8913)
Location: arch/x86/kernel/mpparse.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
