# Function: <code>nvdimm_get_user_key_payload</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8173e556)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
```
**Symbols:**

```
ffffffff8173dae0-ffffffff8173dbad: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff817621d7)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81761960-ffffffff81761a2d: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81821721)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81830431)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81814554)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
```
**Symbols:**

```
ffffffff81813560-ffffffff81813630: nvdimm_get_user_key_payload.part.0.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8189ec78)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
```
**Symbols:**

```
ffffffff8189db90-ffffffff8189dc5d: nvdimm_get_user_key_payload.part.0.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *nvdimm_get_user_key_payload(struct nvdimm *nvdimm, key_serial_t id, int subclass, struct key **key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff819e7600)
Location: drivers/nvdimm/security.c:120
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
```
**Symbols:**

```
ffffffff819e7600-ffffffff819e7727: nvdimm_get_user_key_payload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *nvdimm_get_user_key_payload(struct nvdimm *nvdimm, key_serial_t id, int subclass, struct key **key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81b63840)
Location: drivers/nvdimm/security.c:120
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
```
**Symbols:**

```
ffffffff81b63840-ffffffff81b6396b: nvdimm_get_user_key_payload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *nvdimm_get_user_key_payload(struct nvdimm *nvdimm, key_serial_t id, int subclass, struct key **key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81bb6e40)
Location: drivers/nvdimm/security.c:120
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
```
**Symbols:**

```
ffffffff81bb6e40-ffffffff81bb6f5f: nvdimm_get_user_key_payload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *nvdimm_get_user_key_payload(struct nvdimm *nvdimm, key_serial_t id, int subclass, struct key **key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81c0b490)
Location: drivers/nvdimm/security.c:120
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
```
**Symbols:**

```
ffffffff81c0b490-ffffffff81c0b5af: nvdimm_get_user_key_payload (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffff80001096230c)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffff8000109618b0-ffff8000109619ac: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (c000000000a17fbc)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
c000000000a17470-c000000000a175f0: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffe0005cf842)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffe0005cf11c-ffffffe0005cf1fc: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff817168c7)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81716050-ffffffff8171611d: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff816ea347)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff816e9ad0-ffffffff816e9b9d: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81755697)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81754e20-ffffffff81754eed: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81770b07)
Location: drivers/nvdimm/security.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81770290-ffffffff8177035d: nvdimm_get_user_key_payload.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
