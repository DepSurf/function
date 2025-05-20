# Function: <code>get_e820_md5</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_e820_md5(struct e820map *map, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff8178d5a0)
Location: arch/x86/power/hibernate_64.c:203
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8178d5a0-ffffffff8178d6f4: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff817ab730)
Location: arch/x86/power/hibernate_64.c:224
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff817ab730-ffffffff817ab884: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff81822ca0)
Location: arch/x86/power/hibernate_64.c:224
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff81822ca0-ffffffff81822df4: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff8186cf90)
Location: arch/x86/power/hibernate_64.c:234
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate_64.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8186cf90-ffffffff8186d0e2: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff8188f080)
Location: arch/x86/power/hibernate.c:74
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8188f080-ffffffff8188f12e: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff818d9080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff818d9080-ffffffff818d9134: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff8190b080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8190b080-ffffffff8190b134: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff81bbc0a0)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff81bbc0a0-ffffffff81bbc154: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff81bd1080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff81bd1080-ffffffff81bd1134: get_e820_md5 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff818ab080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff818ab080-ffffffff818ab134: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff81865080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff81865080-ffffffff81865134: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff818fc080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff818fc080-ffffffff818fc134: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table *table, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff8191d080)
Location: arch/x86/power/hibernate.c:75
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8191d080-ffffffff8191d134: get_e820_md5 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct e820_table *table</code>
</li>
<li>
<b>Param removed. </b>
<code>struct e820map *map</code>
</li>
</ul>
</details>
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
