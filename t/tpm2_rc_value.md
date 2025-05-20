# Function: <code>tpm2_rc_value</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815ba4df)
Location: drivers/char/tpm/tpm.h:553
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc262)
Location: drivers/char/tpm/tpm.h:553
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620c62)
Location: drivers/char/tpm/tpm.h:552
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8162271a)
Location: drivers/char/tpm/tpm.h:552
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165aa7e)
Location: drivers/char/tpm/tpm.h:572
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c504)
Location: drivers/char/tpm/tpm.h:572
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816789fe)
Location: drivers/char/tpm/tpm.h:555
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81679874)
Location: drivers/char/tpm/tpm.h:555
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816aeebf)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816afe83)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d1baf)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816d2b83)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a3c08)
Location: include/linux/tpm.h:392
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81786ed1)
Location: include/linux/tpm.h:392
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c13ff)
Location: include/linux/tpm.h:392
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8179dfe1)
Location: include/linux/tpm.h:392
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c7970)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff817809a1)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8152045b)
Location: include/linux/tpm.h:402
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81806db1)
Location: include/linux/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b3ba5)
Location: include/linux/tpm.h:412
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff819469c0)
Location: include/linux/tpm.h:412
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165e885)
Location: include/linux/tpm.h:412
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81aa9c40)
Location: include/linux/tpm.h:412
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816971d5)
Location: include/linux/tpm.h:416
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81af5280)
Location: include/linux/tpm.h:416
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d3855)
Location: include/linux/tpm.h:416
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81b48870)
Location: include/linux/tpm.h:416
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bc5ac)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd748)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b5960)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (c09b6b74)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095e090)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (c00000000095f63c)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056e376)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fbce)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816975ff)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816985d3)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81674fef)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81675fc3)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c586f)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816c6843)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816dfd8e)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816e0d31)
Location: drivers/char/tpm/tpm.h:432
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
</details>
</li>
</ul>

## Differences
