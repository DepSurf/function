# Function: <code>match_endpoint</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a5cd0)
Location: drivers/usb/core/usb.c:77
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff816a5cd0-ffffffff816a5d7b: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817110a0)
Location: drivers/usb/core/usb.c:77
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff817110a0-ffffffff8171114b: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8174fe20)
Location: drivers/usb/core/usb.c:77
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff8174fe20-ffffffff8174fecd: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81774250)
Location: drivers/usb/core/usb.c:77
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff81774250-ffffffff817742fd: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817b2380)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff817b2380-ffffffff817b242d: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817e2ab0)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff817e2ab0-ffffffff817e2b5d: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818b1600)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff818b1600-ffffffff818b16ad: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818bffb0)
Location: drivers/usb/core/usb.c:74
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff818bffb0-ffffffff818c005d: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818a3180)
Location: drivers/usb/core/usb.c:74
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff818a3180-ffffffff818a3241: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81937d00)
Location: drivers/usb/core/usb.c:74
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff81937d00-ffffffff81937dc1: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81a8f3f0)
Location: drivers/usb/core/usb.c:74
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff81a8f3f0-ffffffff81a8f514: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c11080)
Location: drivers/usb/core/usb.c:74
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff81c11080-ffffffff81c111a4: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c77ce0)
Location: drivers/usb/core/usb.c:74
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff81c77ce0-ffffffff81c77e2c: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2c6e0)
Location: drivers/usb/core/usb.c:75
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff81d2c6e0-ffffffff81d2c82c: match_endpoint (STB_LOCAL)
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
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a10d80)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffff800010a10d80-ffff800010a10e94: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0ae9494)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
c0ae9494-c0ae95c8: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac7c30)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
c000000000ac7c30-c000000000ac7d70: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe000636a4a)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffe000636a4a-ffffffe000636b20: match_endpoint (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8179ae90)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff8179ae90-ffffffff8179af3d: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8178cb20)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff8178cb20-ffffffff8178cbcd: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817d7930)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff817d7930-ffffffff817d79dd: match_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool match_endpoint(struct usb_endpoint_descriptor *epd, struct usb_endpoint_descriptor **bulk_in, struct usb_endpoint_descriptor **bulk_out, struct usb_endpoint_descriptor **int_in, struct usb_endpoint_descriptor **int_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817f1bd0)
Location: drivers/usb/core/usb.c:76
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_find_common_endpoints_reverse
  - drivers/usb/core/usb.c:usb_find_common_endpoints
```
**Symbols:**

```
ffffffff817f1bd0-ffffffff817f1c7d: match_endpoint (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
