# Function: <code>load_uefi_certs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/modsign_uefi.c (ffffffff81faa0c2)
Location: kernel/modsign_uefi.c:61
Inline: False
```
**Symbols:**

```
ffffffff81faa0c2-ffffffff81faa363: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/modsign_uefi.c (ffffffff81fe60ce)
Location: kernel/modsign_uefi.c:61
Inline: False
```
**Symbols:**

```
ffffffff81fe60ce-ffffffff81fe636f: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff820cdaaf)
Location: certs/load_uefi.c:140
Inline: False
```
**Symbols:**

```
ffffffff820cdaaf-ffffffff820cdcbd: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff826d64e5)
Location: certs/load_uefi.c:140
Inline: False
```
**Symbols:**

```
ffffffff826d64e5-ffffffff826d66f3: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff82700b08)
Location: certs/load_uefi.c:149
Inline: False
```
**Symbols:**

```
ffffffff82700b08-ffffffff82700d4a: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int load_uefi_certs();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff828b78ef)
Location: certs/load_uefi.c:140
Inline: False
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cf91e)
Location: security/integrity/platform_certs/load_uefi.c:150
Inline: False
```
**Symbols:**

```
ffffffff828b78ef-ffffffff828b7aff: load_uefi_certs (STB_LOCAL)
ffffffff828cf91e-ffffffff828cfb60: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e961a)
Location: security/integrity/platform_certs/load_uefi.c:150
Inline: False
```
**Symbols:**

```
ffffffff828e961a-ffffffff828e9861: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828f20d6)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
ffffffff828f20d6-ffffffff828f23b7: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff82d070e1)
Location: security/integrity/platform_certs/load_uefi.c:75
Inline: False
```
**Symbols:**

```
ffffffff82d070e1-ffffffff82d07377: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff82ff4650)
Location: security/integrity/platform_certs/load_uefi.c:134
Inline: False
```
**Symbols:**

```
ffffffff82ff4650-ffffffff82ff4836: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff831ff28e)
Location: security/integrity/platform_certs/load_uefi.c:149
Inline: False
```
**Symbols:**

```
ffffffff831ff28e-ffffffff831ff4c4: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff832e667d)
Location: security/integrity/platform_certs/load_uefi.c:149
Inline: False
```
**Symbols:**

```
ffffffff832e667d-ffffffff832e68ad: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff8349d6a8)
Location: security/integrity/platform_certs/load_uefi.c:176
Inline: False
```
**Symbols:**

```
ffffffff8349d6a8-ffffffff8349d911: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff83ed5290)
Location: security/integrity/platform_certs/load_uefi.c:177
Inline: False
```
**Symbols:**

```
ffffffff83ed5290-ffffffff83ed5547: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff836fa3f0)
Location: security/integrity/platform_certs/load_uefi.c:177
Inline: False
```
**Symbols:**

```
ffffffff836fa3f0-ffffffff836fa6a7: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff8392d8b0)
Location: security/integrity/platform_certs/load_uefi.c:177
Inline: False
```
**Symbols:**

```
ffffffff8392d8b0-ffffffff8392db67: load_uefi_certs (STB_LOCAL)
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
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffff80001146c4b4)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
ffff80001146c4b4-ffff80001146c788: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (c1545128)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
c1545128-c1545408: load_uefi_certs (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828daf8a)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
ffffffff828daf8a-ffffffff828db26b: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828d36a6)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
ffffffff828d36a6-ffffffff828d3987: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828edcfe)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
ffffffff828edcfe-ffffffff828edfdf: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int load_uefi_certs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828f3120)
Location: security/integrity/platform_certs/load_uefi.c:80
Inline: False
```
**Symbols:**

```
ffffffff828f3120-ffffffff828f3401: load_uefi_certs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
