# Function: <code>security_update</code>

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
In drivers/nvdimm/security.c (ffffffff81762188)
Location: drivers/nvdimm/security.c:275
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
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81821fb0)
Location: drivers/nvdimm/security.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81821fb0-ffffffff818222d4: security_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81830cc0)
Location: drivers/nvdimm/security.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81830cc0-ffffffff81830fe4: security_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81813d90)
Location: drivers/nvdimm/security.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81813d90-ffffffff818140af: security_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff8189e400-ffffffff8189e741: security_update (STB_LOCAL)
ffffffff81d0b7f4-ffffffff81d0b81e: security_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff819e7b30-ffffffff819e7e5e: security_update (STB_LOCAL)
ffffffff81ed462e-ffffffff81ed4658: security_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:296
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81b643a0-ffffffff81b646ce: security_update (STB_LOCAL)
ffffffff8209b54c-ffffffff8209b576: security_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:296
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81bb7cf0-ffffffff81bb8017: security_update (STB_LOCAL)
ffffffff8211c445-ffffffff8211c46f: security_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_update(struct nvdimm *nvdimm, unsigned int keyid, unsigned int new_keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:296
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81c0c340-ffffffff81c0c667: security_update (STB_LOCAL)
ffffffff821fa2cc-ffffffff821fa2f6: security_update.cold (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffff80001096200c)
Location: drivers/nvdimm/security.c:275
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
In drivers/nvdimm/security.c (c000000000a18110)
Location: drivers/nvdimm/security.c:275
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
In drivers/nvdimm/security.c (ffffffe0005cf8d4)
Location: drivers/nvdimm/security.c:275
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
In drivers/nvdimm/security.c (ffffffff81716878)
Location: drivers/nvdimm/security.c:275
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
In drivers/nvdimm/security.c (ffffffff816ea2f8)
Location: drivers/nvdimm/security.c:275
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
In drivers/nvdimm/security.c (ffffffff81755648)
Location: drivers/nvdimm/security.c:275
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
In drivers/nvdimm/security.c (ffffffff81770ab8)
Location: drivers/nvdimm/security.c:275
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
