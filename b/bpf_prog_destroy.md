# Function: <code>bpf_prog_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731cf0)
Location: net/core/filter.c:1136
Inline: False
Direct callers:
  - kernel/seccomp.c:put_seccomp_filter
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff81731cf0-ffffffff81731d00: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d157)
Location: net/core/filter.c:1164
Inline: True
Inline callers:
  - net/core/filter.c:__reuseport_attach_prog
Direct callers:
  - kernel/seccomp.c:put_seccomp_filter
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff8179d100-ffffffff8179d110: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cac07)
Location: net/core/filter.c:1166
Inline: True
Inline callers:
  - net/core/filter.c:__reuseport_attach_prog
Direct callers:
  - kernel/seccomp.c:put_seccomp_filter
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff817cabb0-ffffffff817cabc0: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9d87)
Location: net/core/filter.c:1191
Inline: True
Inline callers:
  - net/core/filter.c:__reuseport_attach_prog
Direct callers:
  - kernel/seccomp.c:put_seccomp_filter
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff817e9d30-ffffffff817e9d40: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818653f7)
Location: net/core/filter.c:1212
Inline: True
Inline callers:
  - net/core/filter.c:__reuseport_attach_prog
Direct callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff818653a0-ffffffff818653b0: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2f97)
Location: net/core/filter.c:1424
Inline: True
Inline callers:
  - net/core/filter.c:__reuseport_attach_prog
Direct callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff818b2f40-ffffffff818b2f50: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818df054)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff818d7e20-ffffffff818d7e30: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192cf54)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff819258c0-ffffffff819258d0: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195f254)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff81957cf0-ffffffff81957d00: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a3263d)
Location: net/core/filter.c:1415
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a2d650-ffffffff81a2d699: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a3497d)
Location: net/core/filter.c:1445
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81a2f110-ffffffff81a2f159: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1b9ed)
Location: net/core/filter.c:1445
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a164f0-ffffffff81a16539: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acf0cd)
Location: net/core/filter.c:1446
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81ac79a0-ffffffff81ac79e9: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4c7cc)
Location: net/core/filter.c:1447
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81c447c0-ffffffff81c44813: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e015bc)
Location: net/core/filter.c:1449
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81df86b0-ffffffff81df8703: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e7307c)
Location: net/core/filter.c:1449
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81e6a1f0-ffffffff81e6a243: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f327fc)
Location: net/core/filter.c:1454
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81f292e0-ffffffff81f29333: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c0274c)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffff800010bf9348-ffff800010bf9374: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1bc14)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
c0d12f54-c0d12f70: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cebbe4)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
c000000000ce0740-c000000000ce0754: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000781ae2)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffe00077b336-ffffffe00077b360: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ff224)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff818f7cc0-ffffffff818f7cd0: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b9054)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff818b1af0-ffffffff818b1b00: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81950254)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff81948cf0-ffffffff81948d00: bpf_prog_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_destroy(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81971c24)
Location: net/core/filter.c:1426
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__put_seccomp_filter
  - drivers/net/tun.c:tun_prog_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff8196a600-ffffffff8196a610: bpf_prog_destroy (STB_GLOBAL)
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
