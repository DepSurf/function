# Function: <code>gnttab_end_foreign_access_ref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c4cc0)
Location: drivers/xen/grant-table.c:290
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814c4cc0-ffffffff814c4cfc: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515440)
Location: drivers/xen/grant-table.c:289
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81515440-ffffffff8151547c: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815418d0)
Location: drivers/xen/grant-table.c:289
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff815418d0-ffffffff8154190c: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81555720)
Location: drivers/xen/grant-table.c:290
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81555720-ffffffff8155575c: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b9360)
Location: drivers/xen/grant-table.c:344
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff815b9360-ffffffff815b93a2: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:344
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff815f3379-ffffffff815f338f: gnttab_end_foreign_access_ref.cold.26 (STB_LOCAL)
ffffffff815f1910-ffffffff815f1943: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8160e3d9-ffffffff8160e3ef: gnttab_end_foreign_access_ref.cold.27 (STB_LOCAL)
ffffffff8160c5d0-ffffffff8160c603: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff816420e9-ffffffff81642100: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff816402a0-ffffffff816402d7: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff816646a9-ffffffff816646c0: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff81662860-ffffffff81662897: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817129b5)
Location: drivers/xen/grant-table.c:347
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_get_responses
```
**Symbols:**

```
ffffffff81713c49-ffffffff81713c60: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff81711c80-ffffffff81711cb7: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172f75a)
Location: drivers/xen/grant-table.c:347
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_get_responses
```
**Symbols:**

```
ffffffff81c04a55-ffffffff81c04a6c: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff8172ea30-ffffffff8172ea67: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817137bc)
Location: drivers/xen/grant-table.c:347
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_get_responses
```
**Symbols:**

```
ffffffff81bf663e-ffffffff81bf6655: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff817126f0-ffffffff81712727: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:328
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81cf528d-ffffffff81cf52a4: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff8178f190-ffffffff8178f1c7: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:472
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81ebd3e1-ffffffff81ebd3f7: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff818c7320-ffffffff818c735b: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a17c60)
Location: drivers/xen/grant-table.c:472
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81a17c60-ffffffff81a17ca8: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a60cf0)
Location: drivers/xen/grant-table.c:472
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81a60cf0-ffffffff81a60d38: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab3520)
Location: drivers/xen/grant-table.c:470
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81ab3520-ffffffff81ab3568: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082bd28)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffff80001082bd28-ffff80001082bd8c: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8162a519-ffffffff8162a530: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff816286d0-ffffffff81628707: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff816584e9-ffffffff81658500: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff816566a0-ffffffff816566d7: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gnttab_end_foreign_access_ref(grant_ref_t ref, int readonly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:348
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81672ae9-ffffffff81672b00: gnttab_end_foreign_access_ref.cold (STB_LOCAL)
ffffffff81670c80-ffffffff81670cb7: gnttab_end_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int readonly</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
