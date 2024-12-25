Set up vpn server on home router

# Apply public ip address from your ISP
In Singapore, seems only limited number of ISPs provide public ip. 
Such as  M1, MR and VQ provides.

see https://www.m1.com.sg/support/faq/static-ip-service-faq


# Set your optical modem to bridge mode (桥接）
This is to avoid NAT of your modem.
May need to seek help from your ISP


# Get a DDNS
https://www.noip.com/

Even ISP provide public ip address, they usually don't provide static public ip. So you need to use a dynamic dns(DDNS) to create the mapping.


#  Configure the DDNS on your router


# Set up vpn server on your router
e.g. https://www.lazada.sg/products/dynacore-tp-link-archer-ax73-ax5400-dual-band-gigabit-wi-fi-6-router-i1622609268-s10266513163.html?c=&channelLpJumpArgs=&clickTrackInfo=query%253Atp%252Blink%252Bax5400%253Bnid%253A1622609268%253Bsrc%253ALazadaMainSrp%253Brn%253Aa98c5ca5899a2c3bcac9ad465bc309c5%253Bregion%253Asg%253Bsku%253A1622609268_SGAMZ%253Bprice%253A199%253Bclient%253Adesktop%253Bsupplier_id%253A20957%253Bbiz_source%253Ah5_internal%253Bslot%253A0%253Butlog_bucket_id%253A470687%253Basc_category_id%253A128%253Bitem_id%253A1622609268%253Bsku_id%253A10266513163%253Bshop_id%253A1347%253BtemplateInfo%253A-1_A3_C%2523107878_D_E%2523&freeshipping=1&fs_ab=2&fuse_fs=&lang=en&location=Singapore&price=199&priceCompare=skuId%3A10266513163%3Bsource%3Alazada-search-voucher%3Bsn%3Aa98c5ca5899a2c3bcac9ad465bc309c5%3BoriginPrice%3A19900%3BdisplayPrice%3A19900%3BsinglePromotionId%3A-1%3BsingleToolCode%3A-1%3BvoucherPricePlugin%3A0%3Btimestamp%3A1735103373041&ratingscore=4.961538461538462&request_id=a98c5ca5899a2c3bcac9ad465bc309c5&review=26&sale=91&search=1&source=search&spm=a2o42.searchlist.list.0&stock=1


# Connect to your vpn server using the previous ddns


