# Function: <code>nvdimm_key_revalidate</code>

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
In drivers/nvdimm/security.c (ffffffff81703fbb)
Location: drivers/nvdimm/security.c:108
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
In drivers/nvdimm/security.c (ffffffff8173dce7)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (ffffffff81761b64)
Location: drivers/nvdimm/security.c:139
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
int nvdimm_key_revalidate(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81821860)
Location: drivers/nvdimm/security.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81821860-ffffffff818219a8: nvdimm_key_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvdimm_key_revalidate(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81830570)
Location: drivers/nvdimm/security.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81830570-ffffffff818306b8: nvdimm_key_revalidate (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff81813b64)
Location: drivers/nvdimm/security.c:139
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff8189e1b0)
Location: drivers/nvdimm/security.c:139
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff819e7fb0)
Location: drivers/nvdimm/security.c:139
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81b64169)
Location: drivers/nvdimm/security.c:139
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81bb7769)
Location: drivers/nvdimm/security.c:139
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81c0bdb9)
Location: drivers/nvdimm/security.c:139
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffff800010961af0)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (c000000000a177c0)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (ffffffe0005cf302)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (ffffffff81716254)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (ffffffff816e9cd4)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (ffffffff81755024)
Location: drivers/nvdimm/security.c:139
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
In drivers/nvdimm/security.c (ffffffff81770494)
Location: drivers/nvdimm/security.c:139
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
</ul>
