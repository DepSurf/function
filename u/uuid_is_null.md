# Function: <code>uuid_is_null</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815a1519)
Location: drivers/nvdimm/btt_devs.c:206
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815f7939)
Location: drivers/nvdimm/btt_devs.c:225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81625ba9)
Location: drivers/nvdimm/btt_devs.c:225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813f9756)
Location: include/linux/uuid.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81421be8)
Location: include/linux/uuid.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8145445f)
Location: include/linux/uuid.h:69
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8147119c)
Location: include/linux/uuid.h:69
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff8149ebcf)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814b972f)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff8151993c)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff81536c1f)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff8153ea83)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff8159e222)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816432f3)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In drivers/nvdimm/btt_devs.c (ffffffff819e5611)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816fb5b3)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81b614b1)
Location: include/linux/uuid.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81735688)
Location: include/linux/uuid.h:91
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81bb4a6b)
Location: include/linux/uuid.h:91
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81776168)
Location: include/linux/uuid.h:91
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c08feb)
Location: include/linux/uuid.h:91
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
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
In security/integrity/ima/ima_policy.c (ffff8000105b16e8)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0760cc4)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c00000000073163c)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffe0003f8e90)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b1d0f)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In drivers/nvme/host/core.c (ffffffff81746cc8)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:wwid_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814a272f)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In drivers/nvme/host/core.c (ffffffff81728948)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:wwid_show
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
In security/integrity/ima/ima_policy.c (ffffffff814add9f)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814c67ef)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
</ul>

## Differences
