# Function: <code>hard_smp_processor_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810546f0)
Location: arch/x86/kernel/apic/apic.c:2117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff810546f0-ffffffff8105471c: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81054880)
Location: arch/x86/kernel/apic/apic.c:2158
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81054880-ffffffff810548ac: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81057660)
Location: arch/x86/kernel/apic/apic.c:2205
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81057660-ffffffff8105768c: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056d80)
Location: arch/x86/kernel/apic/apic.c:2269
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81056d80-ffffffff81056dac: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105aaf0)
Location: arch/x86/kernel/apic/apic.c:2331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8105aaf0-ffffffff8105ab25: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105d920)
Location: arch/x86/kernel/apic/apic.c:2361
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8105d920-ffffffff8105d955: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810635b0)
Location: arch/x86/kernel/apic/apic.c:2369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff810635b0-ffffffff810635e5: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066c30)
Location: arch/x86/kernel/apic/apic.c:2458
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81066c30-ffffffff81066c65: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810672a0)
Location: arch/x86/kernel/apic/apic.c:2515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff810672a0-ffffffff810672d5: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106deb0)
Location: arch/x86/kernel/apic/apic.c:2473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8106deb0-ffffffff8106dee5: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f650)
Location: arch/x86/kernel/apic/apic.c:2504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8106f650-ffffffff8106f685: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81070180)
Location: arch/x86/kernel/apic/apic.c:2512
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81070180-ffffffff810701b5: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107bca0)
Location: arch/x86/kernel/apic/apic.c:2509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8107bca0-ffffffff8107bcd5: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8108aed0)
Location: arch/x86/kernel/apic/apic.c:2517
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8108aed0-ffffffff8108af0b: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109f0a0)
Location: arch/x86/kernel/apic/apic.c:2551
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff8109f0a0-ffffffff8109f0db: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a2030)
Location: arch/x86/kernel/apic/apic.c:2568
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff810a2030-ffffffff810a206b: hard_smp_processor_id (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066d90)
Location: arch/x86/kernel/apic/apic.c:2515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81066d90-ffffffff81066dc5: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81057160)
Location: arch/x86/kernel/apic/apic.c:2515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81057160-ffffffff81057195: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81067240)
Location: arch/x86/kernel/apic/apic.c:2515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81067240-ffffffff81067275: hard_smp_processor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hard_smp_processor_id();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81068820)
Location: arch/x86/kernel/apic/apic.c:2515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
**Symbols:**

```
ffffffff81068820-ffffffff81068855: hard_smp_processor_id (STB_GLOBAL)
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
