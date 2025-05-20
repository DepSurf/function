# Function: <code>security_disable</code>

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
In drivers/nvdimm/security.c (ffffffff81762230)
Location: drivers/nvdimm/security.c:242
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
int security_disable(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818219b0)
Location: drivers/nvdimm/security.c:242
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff818219b0-ffffffff81821b53: security_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_disable(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818306c0)
Location: drivers/nvdimm/security.c:242
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff818306c0-ffffffff81830863: security_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8181450d)
Location: drivers/nvdimm/security.c:242
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8189ec31)
Location: drivers/nvdimm/security.c:242
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff819e86c0)
Location: drivers/nvdimm/security.c:242
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_disable(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:248
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81b646e0-ffffffff81b64a1a: security_disable (STB_LOCAL)
ffffffff8209b576-ffffffff8209b5a0: security_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_disable(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:248
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81bb79a0-ffffffff81bb7cde: security_disable (STB_LOCAL)
ffffffff8211c41b-ffffffff8211c445: security_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_disable(struct nvdimm *nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:248
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81c0bff0-ffffffff81c0c32e: security_disable (STB_LOCAL)
ffffffff821fa2a2-ffffffff821fa2cc: security_disable.cold (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffff8000109621e8)
Location: drivers/nvdimm/security.c:242
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
In drivers/nvdimm/security.c (c000000000a181ec)
Location: drivers/nvdimm/security.c:242
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
In drivers/nvdimm/security.c (ffffffe0005cfa46)
Location: drivers/nvdimm/security.c:242
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
In drivers/nvdimm/security.c (ffffffff81716920)
Location: drivers/nvdimm/security.c:242
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
In drivers/nvdimm/security.c (ffffffff816ea3a0)
Location: drivers/nvdimm/security.c:242
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
In drivers/nvdimm/security.c (ffffffff817556f0)
Location: drivers/nvdimm/security.c:242
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
In drivers/nvdimm/security.c (ffffffff81770b60)
Location: drivers/nvdimm/security.c:242
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
