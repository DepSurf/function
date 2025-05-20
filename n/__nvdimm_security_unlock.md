# Function: <code>__nvdimm_security_unlock</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81703f65)
Location: drivers/nvdimm/security.c:133
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8173dbd5)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81761a59)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81821da0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81821da0-ffffffff81821fa4: __nvdimm_security_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81830ab0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81830ab0-ffffffff81830cb4: __nvdimm_security_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81813a60)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81813a60-ffffffff81813d8f: __nvdimm_security_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8189e0a0-ffffffff8189e3f1: __nvdimm_security_unlock (STB_LOCAL)
ffffffff81d0b7b5-ffffffff81d0b7f4: __nvdimm_security_unlock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff819e7e60-ffffffff819e81ef: __nvdimm_security_unlock (STB_LOCAL)
ffffffff81ed4658-ffffffff81ed4697: __nvdimm_security_unlock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81b64010-ffffffff81b64389: __nvdimm_security_unlock (STB_LOCAL)
ffffffff8209b50d-ffffffff8209b54c: __nvdimm_security_unlock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81bb7610-ffffffff81bb7989: __nvdimm_security_unlock (STB_LOCAL)
ffffffff8211c3dc-ffffffff8211c41b: __nvdimm_security_unlock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __nvdimm_security_unlock(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81c0bc60-ffffffff81c0bfd9: __nvdimm_security_unlock (STB_LOCAL)
ffffffff821fa263-ffffffff821fa2a2: __nvdimm_security_unlock.cold (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffff8000109619e4)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
In drivers/nvdimm/security.c (c000000000a17648)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffe0005cf232)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff81716149)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff816e9bc9)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff81754f19)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff81770389)
Location: drivers/nvdimm/security.c:165
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
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
