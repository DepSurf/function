# Function: <code>get_handler_for_mok</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_mok(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349da28)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff8349da28-ffffffff8349dac3: get_handler_for_mok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_mok(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed56d0)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff83ed56d0-ffffffff83ed5767: get_handler_for_mok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_mok(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa830)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff836fa830-ffffffff836fa8c7: get_handler_for_mok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_mok(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392dcf0)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff8392dcf0-ffffffff8392dd87: get_handler_for_mok (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
