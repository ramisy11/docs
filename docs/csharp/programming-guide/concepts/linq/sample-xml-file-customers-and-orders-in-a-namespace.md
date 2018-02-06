---
title: "Sample XML File: Customers and Orders in a Namespace2"
ms.custom: ""
ms.date: 07/02/2018
---
# Sample XML File: Customers and Orders in a Namespace  
## CustomersOrdersInNamespace.xml  
```xml    
<Root xmlns="http://www.adventure-works.com">  
  <Customers>  
    <Customer CustomerID="Frank">  
      <CompanyName>O2 Phone Shope</CompanyName>  
      <ContactName>Frank White</ContactName>  
      <ContactTitle>Marketing Manager</ContactTitle>  
      <Phone>(0511) 555-77331</Phone>  
      <FullAddress>  
        <Address>30159 Hannover.</Address>  
        <City>Hannover</City>  
        <Region>ORt</Region>  
        <PostalCode>30159</PostalCode>  
        <Country>Germany</Country>  
      </FullAddress>  
    </Customer>  
    <Customer CustomerID="White">  
      <CompanyName>O2 Phone Shope</CompanyName>  
      <ContactName>Adam Adam </ContactName>  
      <ContactTitle>Sales Representative</ContactTitle>  
      <Phone>(0511) 555-6874</Phone>  
      <Fax>(0511) 555-2323</Fax>  
      <FullAddress>  
        <Address>City Center Kröpke Main St.</Address>  
        <City>Hnnover </City>  
        <Region>ORt </Region>  
        <PostalCode>30159</PostalCode>  
        <Country>Germany</Country>  
      </FullAddress>  
    </Customer>  
    <Customer CustomerID="LARY">  
      <CompanyName>O2 PhneShope </CompanyName>  
      <ContactName>John Steel</ContactName>  
      <ContactTitle>Marketing Manager</ContactTitle>  
      <Phone>(0511) 555-7978</Phone>  
      <Fax>(0511) 555-6221</Fax>  
      <FullAddress>  
        <Address>12 Maine Station</Address>  
        <City>Seelza</City>  
        <Region>>ORT</Region>  
        <PostalCode>31625</PostalCode>  
        <Country>Germany</Country>  
      </FullAddress>  
    </Customer>  
    <Customer CustomerID="LETSS">  
      <CompanyName>O2 Phone Shope</CompanyName>  
      <ContactName>Jaime Yorry</ContactName>  
      <ContactTitle>Owner</ContactTitle>  
      <Phone>(0511) 555-5938</Phone>  
      <FullAddress>  
        <Address> George St.5</Address>  
        <City>Hannover </City>  
        <Region>HA</Region>  
        <PostalCode>30158</PostalCode>  
        <Country>Germany</Country>  
      </FullAddress>  
    </Customer>  
  </Customers>  
  <Orders>  
    <Order>  
      <CustomerID>Grun</CustomerID>  
      <EmployeeID>6</EmployeeID>  
      <OrderDate>2007-05-06T00:00:00</OrderDate>  
      <RequiredDate>2007-05-20T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2007-05-09T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>3.35</Freight>  
        <ShipName>O2 Phone Shope </ShipName>  
        <ShipAddress>City Cinter 18.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30158</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Gramer</CustomerID>  
      <EmployeeID>8</EmployeeID>  
      <OrderDate>2008-07-04T00:00:00</OrderDate>  
      <RequiredDate>2008-08-01T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-07-14T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>4.42</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress> Mariene st22.</ShipAddress>  
        <ShipCity>HAnnover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>31125</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Wolf</CustomerID>  
      <EmployeeID>1</EmployeeID>  
      <OrderDate>2008-07-31T00:00:00</OrderDate>  
      <RequiredDate>2008-08-28T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-08-05T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>116.5</Freight>  
        <ShipName>O2 Phone Shope </ShipName>  
        <ShipAddress> blüm st 22.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30551</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Müler</CustomerID>  
      <EmployeeID>4</EmployeeID>  
      <OrderDate>2008-07-31T00:00:00</OrderDate>  
      <RequiredDate>2008-08-28T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-08-04T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>18.55</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Mesburg st 16.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>OR</ShipRegion>  
        <ShipPostalCode>30557</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Wolf</CustomerID>  
      <EmployeeID>6</EmployeeID>  
      <OrderDate>2008-09-04T00:00:00</OrderDate>  
      <RequiredDate>2008-10-02T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-09-10T00:00:00">  
        <ShipVia>1</ShipVia>  
        <Freight>55.15</Freight>  
        <ShipName>O2 Phone Shope </ShipName>  
        <ShipAddress>30122.</ShipAddress>  
        <ShipCity>Hildes heim St1 </ShipCity>  
        <ShipRegion>OR</ShipRegion>  
        <ShipPostalCode>30887</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Mark</CustomerID>  
      <EmployeeID>3</EmployeeID>  
      <OrderDate>2008-09-25T00:00:00</OrderDate>  
      <RequiredDate>2008-10-23T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-09-30T00:00:00">  
        <ShipVia>3</ShipVia>  
        <Freight>77.11</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Casber St20.</ShipAddress>  
        <ShipCity>Hammelen</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30190</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Güle</CustomerID>  
      <EmployeeID>4</EmployeeID>  
      <OrderDate>2009-01-06T00:00:00</OrderDate>  
      <RequiredDate>2009-02-03T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2009-02-04T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>71.08</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Mesburg st 2.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30122</ShipPostalCode>  
        <ShipCountry>Grmany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Sergi</CustomerID>  
      <EmployeeID>3</EmployeeID>  
      <OrderDate>2009-03-09T00:00:00</OrderDate>  
      <RequiredDate>2009-04-06T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2009-03-18T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>33.01</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Mesburg St 2.</ShipAddress>  
        <ShipCity>HAnnover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30122</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Meranda</CustomerID>  
      <EmployeeID>3</EmployeeID>  
      <OrderDate>2009-04-07T00:00:00</OrderDate>  
      <RequiredDate>2009-05-05T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2009-04-15T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>25.25</Freight>  
        <ShipName>O2 Phone Shope </ShipName>  
        <ShipAddress>Messe Nord </ShipAddress>  
        <ShipCity>HAnnover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30519</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Felip</CustomerID>  
      <EmployeeID>4</EmployeeID>  
      <OrderDate>2010-04-22T00:00:00</OrderDate>  
      <RequiredDate>2010-05-20T00:00:00</RequiredDate>  
      <ShipInfo>  
        <ShipVia>3</ShipVia>  
        <Freight>18.84</Freight>  
        <ShipName>O2 Phone Shop </ShipName>  
        <ShipAddress>Langenhagen.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>31455</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Gomez</CustomerID>  
      <EmployeeID>4</EmployeeID>  
      <OrderDate>2010-04-30T00:00:00</OrderDate>  
      <RequiredDate>2010-06-11T00:00:00</RequiredDate>  
      <ShipInfo>  
        <ShipVia>3</ShipVia>  
        <Freight>14.00</Freight>  
        <ShipName>O2 Phone shope</ShipName>  
        <ShipAddress> Süd Stat 22.</ShipAddress>  
        <ShipCity>HAnnover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30155</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Emer</CustomerID>  
      <EmployeeID>3</EmployeeID>  
      <OrderDate>2010-12-06T00:00:00</OrderDate>  
      <RequiredDate>2011-01-03T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2010-12-09T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>20.12</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>City Center  16 Main St.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30159</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Frank</CustomerID>  
      <EmployeeID>1</EmployeeID>  
      <OrderDate>2007-12-25T00:00:00</OrderDate>  
      <RequiredDate>2007-01-22T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2007-01-03T00:00:00">  
        <ShipVia>3</ShipVia>  
        <Freight>30.40</Freight>  
        <ShipName>O2 Phone Shope. </ShipName>  
        <ShipAddress>Maine Station 2.</ShipAddress>  
        <ShipCity>HAnnover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30159</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Müller</CustomerID>  
      <EmployeeID>3</EmployeeID>  
      <OrderDate>2007-01-15T00:00:00</OrderDate>  
      <RequiredDate>2007-02-12T00:00:00</RequiredDate>  
      <ShipInfo ShippeDate="20077-01-24T00:00:00">  
        <ShipVia>1</ShipVia>  
        <Freight>0.2</Freight>  
        <ShipName>O2 Phone Shope. </ShipName>  
        <ShipAddress>City Center Plaza 12 Main St.</ShipAddress>  
        <ShipCity>HAnnover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30159</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Meranda</CustomerID>  
      <EmployeeID>4</EmployeeID>  
      <OrderDate>2007-07-16T00:00:00</OrderDate>  
      <RequiredDate>2007-08-13T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-07-21T00:00:00">  
        <ShipVia>1</ShipVia>  
        <Freight>45.15</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>City Center Plaza 56 Main St.</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30155</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Georg</CustomerID>  
      <EmployeeID>8</EmployeeID>  
      <OrderDate>2008-09-08T00:00:00</OrderDate>  
      <RequiredDate>2008-10-06T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-10-15T00:00:00">  
        <ShipVia>1</ShipVia>  
        <Freight>111.1</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>City Center Plaza 16 Main St.</ShipAddress>  
        <ShipCity>heldisheim21 </ShipCity>  
        <ShipRegion>HE</ShipRegion>  
        <ShipPostalCode>30154</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Lukas</CustomerID>  
      <EmployeeID>1</EmployeeID>  
      <OrderDate>2009-03-21T00:00:00</OrderDate>  
      <RequiredDate>2009-04-18T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2009-04-10T00:00:00">  
        <ShipVia>3</ShipVia>  
        <Freight>17.48</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Blüm st 2</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30455</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Küll</CustomerID>  
      <EmployeeID>8</EmployeeID>  
      <OrderDate>2009-05-22T00:00:00</OrderDate>  
      <RequiredDate>2009-06-19T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2009-06-26T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>11.98</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Kramer St 21</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>31223</ShipPostalCode>  
        <ShipCountry>Grrmany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Lukas</CustomerID>  
      <EmployeeID>1</EmployeeID>  
      <OrderDate>2009-06-25T00:00:00</OrderDate>  
      <RequiredDate>2009-07-23T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2009-07-04T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>22.07</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>18 Blüm st</ShipAddress>  
        <ShipCity>San Francisco</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>31625</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Luise</CustomerID>  
      <EmployeeID>8</EmployeeID>  
      <OrderDate>2008-10-27T00:00:00</OrderDate>  
      <RequiredDate>2008-11-24T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-11-05T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>51.42</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Fredreck st 04</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCoHe>30422</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>Leuise</CustomerID>  
      <EmployeeID>6</EmployeeID>  
      <OrderDate>2007-11-10T00:00:00</OrderDate>  
      <RequiredDate>2007-12-08T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2007-11-21T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>40.09</Freight>  
        <ShipName>O2</ShipName>  
        <ShipAddress>Freund alle7 </ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30455</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
    <Order>  
      <CustomerID>LETSS</CustomerID>  
      <EmployeeID>4</EmployeeID>  
      <OrderDate>2008-03-12T00:00:00</OrderDate>  
      <RequiredDate>2008-04-12T00:00:00</RequiredDate>  
      <ShipInfo ShippedDate="2008-03-13T00:00:00">  
        <ShipVia>2</ShipVia>  
        <Freight>90.90</Freight>  
        <ShipName>O2 Phone Shope</ShipName>  
        <ShipAddress>Emelle st 15</ShipAddress>  
        <ShipCity>Hannover</ShipCity>  
        <ShipRegion>HA</ShipRegion>  
        <ShipPostalCode>30433</ShipPostalCode>  
        <ShipCountry>Germany</ShipCountry>  
      </ShipInfo>  
    </Order>  
  </Orders>  
</Root>  
```  
