# Function: <code>__fw_load_abort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155e7c0)
Location: drivers/base/firmware_class.c:479
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_shutdown_notify
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:_request_firmware
Direct callers:
  - drivers/base/firmware_class.c:fw_shutdown_notify
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8155e7c0-ffffffff8155e7f4: __fw_load_abort.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b42a9)
Location: drivers/base/firmware_class.c:475
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_shutdown_notify
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff815b2d80-ffffffff815b2dba: __fw_load_abort.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e3658)
Location: drivers/base/firmware_class.c:543
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_shutdown_notify
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff815e2190-ffffffff815e21c6: __fw_load_abort.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f8334)
Location: drivers/base/firmware_class.c:577
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff815f6ef0-ffffffff815f6f29: __fw_load_abort.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff816602fa)
Location: drivers/base/firmware_class.c:581
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff8165ee20-ffffffff8165ee59: __fw_load_abort.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8169bcd1)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff8169b440-ffffffff8169b476: __fw_load_abort.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc45f)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff816bbcc0-ffffffff816bbcf6: __fw_load_abort.part.5 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff816f6bab)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff816f6470-ffffffff816f64ac: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff8171afac)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff8171a870-ffffffff8171a8ac: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff817d6b05)
Location: drivers/base/firmware_loader/fallback.c:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/fallback.c (ffffffff817eb6ab)
Location: drivers/base/firmware_loader/fallback.c:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/fallback.c (ffffffff817cfe7c)
Location: drivers/base/firmware_loader/fallback.c:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/fallback.c (ffffffff8185a69b)
Location: drivers/base/firmware_loader/fallback.c:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __fw_load_abort(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a1819)
Location: drivers/base/firmware_loader/sysfs.c:15
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff819a1880-ffffffff819a18e0: __fw_load_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __fw_load_abort(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b135b9)
Location: drivers/base/firmware_loader/sysfs.c:15
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff81b13630-ffffffff81b13690: __fw_load_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __fw_load_abort(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b618c9)
Location: drivers/base/firmware_loader/sysfs.c:15
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff81b61930-ffffffff81b61990: __fw_load_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __fw_load_abort(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb5359)
Location: drivers/base/firmware_loader/sysfs.c:15
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff81bb53c0-ffffffff81bb5420: __fw_load_abort (STB_GLOBAL)
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
In drivers/base/firmware_loader/fallback.c (ffff80001090e884)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffff80001090deb8-ffff80001090df04: __fw_load_abort.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c09f76fc)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
c09f6e1c-c09f6e64: __fw_load_abort.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009af134)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
c0000000009ae920-c0000000009ae980: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffe000592efe)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffe00059283a-ffffffe00059287a: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff816e12dc)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff816e0ba0-ffffffff816e0bdc: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff816bb91c)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff816bb1e0-ffffffff816bb21c: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff8170e9ac)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff8170e270-ffffffff8170e2ac: __fw_load_abort.part.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff817295cc)
Location: drivers/base/firmware_loader/fallback.c:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
**Symbols:**

```
ffffffff81728e90-ffffffff81728ecc: __fw_load_abort.part.0 (STB_LOCAL)
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
