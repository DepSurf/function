# Function: <code>add_e820_entry</code>

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
In arch/x86/kernel/crash.c (ffffffff8105d20c)
Location: arch/x86/kernel/crash.c:514
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:memmap_entry_callback
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
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
In arch/x86/kernel/crash.c (ffffffff8105d89f)
Location: arch/x86/kernel/crash.c:490
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
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
In arch/x86/kernel/crash.c (ffffffff8106091f)
Location: arch/x86/kernel/crash.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105f3d0)
Location: arch/x86/kernel/crash.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff8105f3d0-ffffffff8105f414: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810633e0)
Location: arch/x86/kernel/crash.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff810633e0-ffffffff81063424: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81066250)
Location: arch/x86/kernel/crash.c:298
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81066250-ffffffff81066294: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8106c250)
Location: arch/x86/kernel/crash.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff8106c250-ffffffff8106c294: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81070250)
Location: arch/x86/kernel/crash.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81070250-ffffffff81070299: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81071250)
Location: arch/x86/kernel/crash.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81071250-ffffffff81071299: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810783c9)
Location: arch/x86/kernel/crash.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:memmap_entry_callback
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81078380-ffffffff810783bd: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810783c9)
Location: arch/x86/kernel/crash.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:memmap_entry_callback
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81078380-ffffffff810783bd: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81079269)
Location: arch/x86/kernel/crash.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:memmap_entry_callback
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81079220-ffffffff8107925d: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810872a5)
Location: arch/x86/kernel/crash.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:memmap_entry_callback
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81087220-ffffffff81087287: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810974b9)
Location: arch/x86/kernel/crash.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:memmap_entry_callback
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81097290-ffffffff8109734c: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810ad890)
Location: arch/x86/kernel/crash.c:260
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff810ad890-ffffffff810ad94c: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b0890)
Location: arch/x86/kernel/crash.c:260
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff810b0890-ffffffff810b094c: add_e820_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b7a50)
Location: arch/x86/kernel/crash.c:233
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff810b7a50-ffffffff810b7b0c: add_e820_entry.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81070250)
Location: arch/x86/kernel/crash.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81070250-ffffffff81070299: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81060250)
Location: arch/x86/kernel/crash.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81060250-ffffffff81060299: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81070250)
Location: arch/x86/kernel/crash.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81070250-ffffffff81070299: add_e820_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params *params, struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81072250)
Location: arch/x86/kernel/crash.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
**Symbols:**

```
ffffffff81072250-ffffffff81072299: add_e820_entry (STB_LOCAL)
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
