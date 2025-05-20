# Function: <code>__threshold_remove_device</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void __threshold_remove_device(struct threshold_bank **bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106ae40)
Location: arch/x86/kernel/cpu/mce/amd.c:1297
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
**Symbols:**

```
ffffffff8106ae40-ffffffff8106b00a: __threshold_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __threshold_remove_device(struct threshold_bank **bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107ad90)
Location: arch/x86/kernel/cpu/mce/amd.c:1304
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
**Symbols:**

```
ffffffff8107ad90-ffffffff8107af5a: __threshold_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __threshold_remove_device(struct threshold_bank **bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107cee0)
Location: arch/x86/kernel/cpu/mce/amd.c:1300
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
**Symbols:**

```
ffffffff8107cee0-ffffffff8107d0a9: __threshold_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __threshold_remove_device(struct threshold_bank **bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810843c0)
Location: arch/x86/kernel/cpu/mce/amd.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
**Symbols:**

```
ffffffff810843c0-ffffffff81084588: __threshold_remove_device (STB_LOCAL)
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
