# Function: <code>load_moklist_certs</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int load_moklist_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff82ff450e)
Location: security/integrity/platform_certs/load_uefi.c:81
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff82ff450e-ffffffff82ff4650: load_moklist_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int load_moklist_certs(const bool load_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff831ff0ef)
Location: security/integrity/platform_certs/load_uefi.c:82
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff831ff0ef-ffffffff831ff28e: load_moklist_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int load_moklist_certs(const bool load_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff832e64e1)
Location: security/integrity/platform_certs/load_uefi.c:82
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff832e64e1-ffffffff832e667d: load_moklist_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int load_moklist_certs(const bool load_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff8349d4f6)
Location: security/integrity/platform_certs/load_uefi.c:109
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff8349d4f6-ffffffff8349d6a8: load_moklist_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int load_moklist_certs(const bool load_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff83ed50b0)
Location: security/integrity/platform_certs/load_uefi.c:110
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff83ed50b0-ffffffff83ed5277: load_moklist_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int load_moklist_certs(const bool load_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff836fa210)
Location: security/integrity/platform_certs/load_uefi.c:110
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff836fa210-ffffffff836fa3dd: load_moklist_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int load_moklist_certs(const bool load_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff8392d6d0)
Location: security/integrity/platform_certs/load_uefi.c:110
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff8392d6d0-ffffffff8392d89d: load_moklist_certs (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const bool load_db</code>
</li>
</ul>
</details>
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
