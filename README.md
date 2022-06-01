NHWC. Another quite popular data format is NHWC, which uses the following offset function: offset_nhwc(n, c, h, w) = n * HWC + h * WC + w * C + c. In this case, the inner-most dimension is channels ( [b:0] ), which is followed by width ( [b:1] ), height ( [b:2] ), and finally batch ( [b:3] ).
