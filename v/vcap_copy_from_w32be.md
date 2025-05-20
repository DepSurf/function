# Function: <code>vcap_copy_from_w32be</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vcap_copy_from_w32be(u8 *dst, u8 *src, int size, int width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf5630)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:860
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_actionfield
```
**Symbols:**

```
ffffffff81bf5630-ffffffff81bf5701: vcap_copy_from_w32be (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vcap_copy_from_w32be(u8 *dst, u8 *src, int size, int width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c59d80)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1056
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_actionfield
```
**Symbols:**

```
ffffffff81c59d80-ffffffff81c59e51: vcap_copy_from_w32be (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vcap_copy_from_w32be(u8 *dst, u8 *src, int size, int width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d10660)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1070
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_copy_to_client_actionfield
```
**Symbols:**

```
ffffffff81d10660-ffffffff81d10731: vcap_copy_from_w32be (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
