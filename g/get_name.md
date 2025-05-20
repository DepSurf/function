# Function: <code>get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_name(const struct path *path, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8130c4f0)
Location: fs/exportfs/expfs.c:270
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff8130c4f0-ffffffff8130c66a: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_name(const struct path *path, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff813407a0)
Location: fs/exportfs/expfs.c:274
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff813407a0-ffffffff81340932: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a7e0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1045
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81356520)
Location: fs/exportfs/expfs.c:274
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff8104a7e0-ffffffff8104a8e6: get_name (STB_LOCAL)
ffffffff81356520-ffffffff813566b2: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a030)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1052
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff8136b110)
Location: fs/exportfs/expfs.c:275
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff8104a030-ffffffff8104a14a: get_name (STB_LOCAL)
ffffffff8136b110-ffffffff8136b2c9: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104da80)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1037
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff8138fca0)
Location: fs/exportfs/expfs.c:275
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff8104da80-ffffffff8104db9a: get_name (STB_LOCAL)
ffffffff8138fca0-ffffffff8138fe59: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810504e0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1089
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff813bed70)
Location: fs/exportfs/expfs.c:275
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff810504e0-ffffffff810505d4: get_name (STB_LOCAL)
ffffffff813bed70-ffffffff813beefc: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104ddb0)
Location: arch/x86/kernel/cpu/mce/amd.c:1089
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff813d83b0)
Location: fs/exportfs/expfs.c:276
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff8104ddb0-ffffffff8104deb2: get_name (STB_LOCAL)
ffffffff813d83b0-ffffffff813d853c: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050c50)
Location: arch/x86/kernel/cpu/mce/amd.c:1169
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81402d50)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff81050c50-ffffffff81050d4f: get_name (STB_LOCAL)
ffffffff81402d50-ffffffff81402ef9: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810515e0)
Location: arch/x86/kernel/cpu/mce/amd.c:1174
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff8141cc60)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff810515e0-ffffffff810516df: get_name (STB_LOCAL)
ffffffff8141cc60-ffffffff8141ce09: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055840)
Location: arch/x86/kernel/cpu/mce/amd.c:1200
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff8146b940)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff81055840-ffffffff8105593f: get_name (STB_LOCAL)
ffffffff8146b940-ffffffff8146bb05: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81054760)
Location: arch/x86/kernel/cpu/mce/amd.c:1200
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81486090)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff81054760-ffffffff8105485f: get_name (STB_LOCAL)
ffffffff81486090-ffffffff81486255: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055f70)
Location: arch/x86/kernel/cpu/mce/amd.c:1200
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff8148bae0)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff81055f70-ffffffff8105606f: get_name (STB_LOCAL)
ffffffff8148bae0-ffffffff8148bc89: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105e9c0)
Location: arch/x86/kernel/cpu/mce/amd.c:1213
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff814e32f0)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff8105e9c0-ffffffff8105ebdb: get_name (STB_LOCAL)
ffffffff814e32f0-ffffffff814e3499: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int cpu, unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b260)
Location: arch/x86/kernel/cpu/mce/amd.c:1037
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81571670)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff8106b260-ffffffff8106b574: get_name (STB_LOCAL)
ffffffff81571670-ffffffff81571835: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int cpu, unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107b230)
Location: arch/x86/kernel/cpu/mce/amd.c:1044
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81616980)
Location: fs/exportfs/expfs.c:276
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff8107b230-ffffffff8107b544: get_name (STB_LOCAL)
ffffffff81616980-ffffffff81616b45: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int cpu, unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107d4d0)
Location: arch/x86/kernel/cpu/mce/amd.c:1040
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff8164ea60)
Location: fs/exportfs/expfs.c:276
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff8107d4d0-ffffffff8107d7f1: get_name (STB_LOCAL)
ffffffff8164ea60-ffffffff8164ec21: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int cpu, unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810847c0)
Location: arch/x86/kernel/cpu/mce/amd.c:1090
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81687fa0)
Location: fs/exportfs/expfs.c:276
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff810847c0-ffffffff81084adb: get_name (STB_LOCAL)
ffffffff81687fa0-ffffffff81688161: get_name (STB_LOCAL)
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
int get_name(const struct path *path, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffff8000104fe868)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffff8000104fe868-ffff8000104fe9e4: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_name(const struct path *path, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c06bb900)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
c06bb900-c06bbaac: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_name(const struct path *path, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c000000000641bb0)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
c000000000641bb0-c000000000641dd8: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_name(const struct path *path, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffe00036c7ce)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffe00036c7ce-ffffffe00036c8f4: get_name (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810516e0)
Location: arch/x86/kernel/cpu/mce/amd.c:1174
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81415240)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff810516e0-ffffffff810517df: get_name (STB_LOCAL)
ffffffff81415240-ffffffff814153e9: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81040840)
Location: arch/x86/kernel/cpu/mce/amd.c:1174
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81405cc0)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff81040840-ffffffff8104093f: get_name (STB_LOCAL)
ffffffff81405cc0-ffffffff81405e69: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051590)
Location: arch/x86/kernel/cpu/mce/amd.c:1174
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff814125c0)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff81051590-ffffffff8105168f: get_name (STB_LOCAL)
ffffffff814125c0-ffffffff81412769: get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *get_name(unsigned int bank, struct threshold_block *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810529d0)
Location: arch/x86/kernel/cpu/mce/amd.c:1174
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In fs/exportfs/expfs.c (ffffffff81428230)
Location: fs/exportfs/expfs.c:277
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_get_name
```
**Symbols:**

```
ffffffff810529d0-ffffffff81052acf: get_name (STB_LOCAL)
ffffffff81428230-ffffffff814283d9: get_name (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param added. </b>
<code>struct threshold_block *b</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param removed. </b>
<code>char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *child</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>bank, b</code> ➡️ <code>cpu, bank, b</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>char *name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry *child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block *b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>char *name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry *child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block *b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>char *name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry *child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block *b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>char *name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry *child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block *b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
