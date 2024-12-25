# install vpn
https://github.com/angristan/openvpn-install

default to UDP mode.
Need to manually configure public ip address

After this step, the wizard will generate a .opvn file, download to your local PC.

# Configure security groups
Whitelist the UDP port that you just configured for incoming traffic.

# buy a tplink router which supports openvpn
e.g.
https://www.lazada.sg/products/dynacore-tp-link-archer-ax73-ax5400-dual-band-gigabit-wi-fi-6-router-i1622609268-s10266513163.html?c=&channelLpJumpArgs=&clickTrackInfo=query%253Atp%252Blink%252Bax5400%253Bnid%253A1622609268%253Bsrc%253ALazadaMainSrp%253Brn%253Abe9f74b440f433ff464cc279027181b0%253Bregion%253Asg%253Bsku%253A1622609268_SGAMZ%253Bprice%253A199%253Bclient%253Adesktop%253Bsupplier_id%253A20957%253Bbiz_source%253Ah5_internal%253Bslot%253A0%253Butlog_bucket_id%253A470687%253Basc_category_id%253A128%253Bitem_id%253A1622609268%253Bsku_id%253A10266513163%253Bshop_id%253A1347%253BtemplateInfo%253A-1_A3_C%2523107878_D_E%2523&freeshipping=1&fs_ab=2&fuse_fs=&lang=en&location=Singapore&price=199&priceCompare=skuId%3A10266513163%3Bsource%3Alazada-search-voucher%3Bsn%3Abe9f74b440f433ff464cc279027181b0%3BoriginPrice%3A19900%3BdisplayPrice%3A19900%3BsinglePromotionId%3A-1%3BsingleToolCode%3A-1%3BvoucherPricePlugin%3A0%3Btimestamp%3A1735099646888&ratingscore=4.961538461538462&request_id=be9f74b440f433ff464cc279027181b0&review=26&sale=91&search=1&source=search&spm=a2o42.searchlist.list.0&stock=1


# Setup ovpn client on tplink router 
Just use the previous .ovpn file


