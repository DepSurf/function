# Function: <code>security_erase</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8176231a)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81821b60)
Location: drivers/nvdimm/security.c:325
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81821b60-ffffffff81821d92: security_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81830870)
Location: drivers/nvdimm/security.c:325
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81830870-ffffffff81830aa2: security_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81813810)
Location: drivers/nvdimm/security.c:325
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81813810-ffffffff81813a5b: security_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:325
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff8189de40-ffffffff8189e094: security_erase (STB_LOCAL)
ffffffff81d0b7a0-ffffffff81d0b7b5: security_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:325
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff819e78d0-ffffffff819e7b30: security_erase (STB_LOCAL)
ffffffff81ed4619-ffffffff81ed462e: security_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:346
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81b63b30-ffffffff81b63d7f: security_erase (STB_LOCAL)
ffffffff8209b4ce-ffffffff8209b4e3: security_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:346
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81bb7120-ffffffff81bb737a: security_erase (STB_LOCAL)
ffffffff8211c39d-ffffffff8211c3b2: security_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_erase(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:346
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81c0b770-ffffffff81c0b9ca: security_erase (STB_LOCAL)
ffffffff821fa224-ffffffff821fa239: security_erase.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffff800010962108)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (c000000000a182f4)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffe0005cf95c)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
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
In drivers/nvdimm/security.c (ffffffff81716a0a)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff816ea48a)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff817557da)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff81770c4a)
Location: drivers/nvdimm/security.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
