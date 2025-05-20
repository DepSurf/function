# Function: <code>nvdimm_put_key</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81704788)
Location: drivers/nvdimm/security.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81703e30-ffffffff81703e51: nvdimm_put_key.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8173e57a)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8173dab0-ffffffff8173dad3: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff81762209)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81761930-ffffffff81761953: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff8182174f)
Location: drivers/nvdimm/security.c:36
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
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
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
In drivers/nvdimm/security.c (ffffffff8183045f)
Location: drivers/nvdimm/security.c:36
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
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
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
In drivers/nvdimm/security.c (ffffffff8181458a)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff8189ecae)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff819e8839)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff81b63a68)
Location: drivers/nvdimm/security.c:36
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
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff81bb7058)
Location: drivers/nvdimm/security.c:36
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
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffffffff81c0b6a8)
Location: drivers/nvdimm/security.c:36
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
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
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
In drivers/nvdimm/security.c (ffff800010962334)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffff800010961878-ffff8000109618ac: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (c000000000a17ff8)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
c000000000a17420-c000000000a17470: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffe0005cf872)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffe0005cf0e6-ffffffe0005cf11c: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff817168f9)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81716020-ffffffff81716043: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff816ea379)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816e9aa0-ffffffff816e9ac3: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff817556c9)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81754df0-ffffffff81754e13: nvdimm_put_key.part.0 (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffffffff81770b39)
Location: drivers/nvdimm/security.c:36
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81770260-ffffffff81770283: nvdimm_put_key.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
