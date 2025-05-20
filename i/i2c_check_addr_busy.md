# Function: <code>i2c_check_addr_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81678e80)
Location: drivers/i2c/i2c-core.c:945
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
**Symbols:**

```
ffffffff81678e80-ffffffff81678edb: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816da180)
Location: drivers/i2c/i2c-core.c:1078
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
  - drivers/i2c/i2c-core.c:i2c_new_device
```
**Symbols:**

```
ffffffff816da180-ffffffff816da1db: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170a750)
Location: drivers/i2c/i2c-core.c:1215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
  - drivers/i2c/i2c-core.c:i2c_new_device
```
**Symbols:**

```
ffffffff8170a750-ffffffff8170a7ab: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171efc0)
Location: drivers/i2c/i2c-core-base.c:617
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff8171efc0-ffffffff8171f016: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81790270)
Location: drivers/i2c/i2c-core-base.c:622
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff81790270-ffffffff817902c6: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d2d80)
Location: drivers/i2c/i2c-core-base.c:603
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff817d2d80-ffffffff817d2dd7: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817f9e70)
Location: drivers/i2c/i2c-core-base.c:615
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff817f9e70-ffffffff817f9ec7: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183abb0)
Location: drivers/i2c/i2c-core-base.c:613
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8183abb0-ffffffff8183ac07: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186c540)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8186c540-ffffffff8186c597: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81940260)
Location: drivers/i2c/i2c-core-base.c:628
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81940260-ffffffff819402b6: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819463d0)
Location: drivers/i2c/i2c-core-base.c:756
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff819463d0-ffffffff81946426: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81929c10)
Location: drivers/i2c/i2c-core-base.c:800
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81929c10-ffffffff81929c66: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819ccd60)
Location: drivers/i2c/i2c-core-base.c:801
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff819ccd60-ffffffff819ccdb6: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2e9e0)
Location: drivers/i2c/i2c-core-base.c:802
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81b2e9e0-ffffffff81b2ea40: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2660)
Location: drivers/i2c/i2c-core-base.c:803
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81cc2660-ffffffff81cc26c0: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a080)
Location: drivers/i2c/i2c-core-base.c:818
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81d2a080-ffffffff81d2a0e0: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81ddff40)
Location: drivers/i2c/i2c-core-base.c:821
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81ddff40-ffffffff81ddffa0: i2c_check_addr_busy (STB_LOCAL)
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
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aaf040)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffff800010aaf040-ffff800010aaf0b0: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b90bf0)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
c0b90bf0-c0b90c60: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b91c20)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
c000000000b91c20-c000000000b91cac: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b771e)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffe0006b771e-ffffffe0006b7780: i2c_check_addr_busy (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818606d0)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff818606d0-ffffffff81860727: i2c_check_addr_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int i2c_check_addr_busy(struct i2c_adapter *adapter, int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187b8e0)
Location: drivers/i2c/i2c-core-base.c:618
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8187b8e0-ffffffff8187b937: i2c_check_addr_busy (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
