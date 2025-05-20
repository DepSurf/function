# Function: <code>alloc_fw_cache_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155efe0)
Location: drivers/base/firmware_class.c:1418
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_create_fw_entry
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8155efe0-ffffffff8155f037: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b3520)
Location: drivers/base/firmware_class.c:1466
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_create_fw_entry
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815b3520-ffffffff815b357f: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e28b0)
Location: drivers/base/firmware_class.c:1501
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_create_fw_entry
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815e28b0-ffffffff815e290f: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f75f0)
Location: drivers/base/firmware_class.c:1501
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_create_fw_entry
  - drivers/base/firmware_class.c:assign_firmware_buf
```
**Symbols:**

```
ffffffff815f75f0-ffffffff815f7647: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165f580)
Location: drivers/base/firmware_class.c:1508
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_create_fw_entry
  - drivers/base/firmware_class.c:assign_firmware_buf
```
**Symbols:**

```
ffffffff8165f580-ffffffff8165f5d7: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81699fc0)
Location: drivers/base/firmware_loader/main.c:925
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81699fc0-ffffffff8169a017: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba5c0)
Location: drivers/base/firmware_loader/main.c:934
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816ba5c0-ffffffff816ba617: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f48a0)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816f48a0-ffffffff816f48fb: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81718ca0)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81718ca0-ffffffff81718cfb: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d505c)
Location: drivers/base/firmware_loader/main.c:1155
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_cache_piggyback_on_request
```
**Symbols:**

```
ffffffff817d4e70-ffffffff817d4ecb: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e992c)
Location: drivers/base/firmware_loader/main.c:1228
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_cache_piggyback_on_request
```
**Symbols:**

```
ffffffff817e96a0-ffffffff817e96fb: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce11c)
Location: drivers/base/firmware_loader/main.c:1232
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817cdea0-ffffffff817cdefb: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff818589bc)
Location: drivers/base/firmware_loader/main.c:1231
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff818586f0-ffffffff8185874b: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199f651)
Location: drivers/base/firmware_loader/main.c:1256
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8199f330-ffffffff8199f399: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b110d1)
Location: drivers/base/firmware_loader/main.c:1256
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81b10d70-ffffffff81b10dd9: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5f361)
Location: drivers/base/firmware_loader/main.c:1311
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81b5f000-ffffffff81b5f069: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2d1e)
Location: drivers/base/firmware_loader/main.c:1312
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81bb2980-ffffffff81bb2a19: alloc_fw_cache_entry (STB_LOCAL)
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
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090c068)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffff80001090c068-ffff80001090c0d0: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f531c)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c09f531c-c09f5388: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009acd40)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c0000000009acd40-c0000000009acde4: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
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
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816defd0)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816defd0-ffffffff816df02b: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b9610)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816b9610-ffffffff816b966b: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170c960)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8170c960-ffffffff8170c9bb: alloc_fw_cache_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fw_cache_entry *alloc_fw_cache_entry(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727310)
Location: drivers/base/firmware_loader/main.c:1124
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81727310-ffffffff8172736b: alloc_fw_cache_entry (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
