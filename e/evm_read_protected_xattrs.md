# Function: <code>evm_read_protected_xattrs</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int evm_read_protected_xattrs(struct dentry *dentry, u8 *buffer, int buffer_size, char type, bool canonical_fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff815a2cd0)
Location: security/integrity/evm/evm_main.c:339
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
```
**Symbols:**

```
ffffffff815a2cd0-ffffffff815a2df7: evm_read_protected_xattrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int evm_read_protected_xattrs(struct dentry *dentry, u8 *buffer, int buffer_size, char type, bool canonical_fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81649420)
Location: security/integrity/evm/evm_main.c:339
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
```
**Symbols:**

```
ffffffff81649420-ffffffff8164957a: evm_read_protected_xattrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evm_read_protected_xattrs(struct dentry *dentry, u8 *buffer, int buffer_size, char type, bool canonical_fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81702260)
Location: security/integrity/evm/evm_main.c:333
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
```
**Symbols:**

```
ffffffff81702260-ffffffff817023ae: evm_read_protected_xattrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evm_read_protected_xattrs(struct dentry *dentry, u8 *buffer, int buffer_size, char type, bool canonical_fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8173c1d0)
Location: security/integrity/evm/evm_main.c:332
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
```
**Symbols:**

```
ffffffff8173c1d0-ffffffff8173c31e: evm_read_protected_xattrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evm_read_protected_xattrs(struct dentry *dentry, u8 *buffer, int buffer_size, char type, bool canonical_fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8177cfa0)
Location: security/integrity/evm/evm_main.c:346
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
```
**Symbols:**

```
ffffffff8177cfa0-ffffffff8177d0ee: evm_read_protected_xattrs (STB_GLOBAL)
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
