# Personal data
Name: Alexandra
Surname: Pagoda
City: Minsk
Contact information: 
Phone: +375336496686 (Life, Viber, Telegram)
Email: a.pagoda@inbox.ru
Bitbucket: bitbucket.org/sshagd/

# Summary and skills
- Java SE
- Java EE
- JavaScript
- SQL
- HTML
- CSS
#### English level
English level: B1

# Education

| Category | Information |
| ------ | ------ |
| ***University*** | Belarusian National Technical University |
| Faculty | Faculty of Information Technologies and Robotics |
| Speciality | Automation of Technological Processes and Production |
| Period | 2016-2021 |
| Basis | Full-time |
| ***Training*** | EPAM Systems |
| Speciality | Java Web Development |
| Period | 2018-2019 |

# Experience
  - Information Technology Center of the Ministry of Labour and Social Protection Republic of Belarus
Duration: 11 months
Position: software engineer

# My code example
```
<xs:complexType name="tariff">
                <xs:attribute name="id" type="xs:ID" use="required"/>
                <xs:attribute name="name" type="xs:string" use="required"/>
                <xs:attribute name="operator_name" type="xs:string" use="required"/>
                <xs:attribute name="payroll" type="xs:double" use="required"/>
        </xs:complexType>

                <xs:element name="call_prices">
                    <xs:complexType>
                        <xs:sequence>
                            <xs:element name="internal_calls" type="xs:double"/>
                            <xs:element name="external_calls" type="xs:double"/>
                            <xs:element name="landline_calls" type="xs:double"/>
                        </xs:sequence>
                    </xs:complexType>
                </xs:element>

                <xs:element name="SMS_price" type="xs:double"/>

                <xs:complexType name="parameters">
                            <xs:attribute name="favourite_number" type="xs:boolean" default="false"/>
                            <xs:attribute name="tarification" default="minute">
                                <xs:simpleType>
                                    <xs:restriction base="xs:string">
                                        <xs:enumeration value="12 seconds">
                                        </xs:enumeration>
                                        <xs:enumeration value="20 seconds">
                                        </xs:enumeration>
                                        <xs:enumeration value="30 seconds">
                                        </xs:enumeration>
                                        <xs:enumeration value="minute">
                                        </xs:enumeration>
                                    </xs:restriction>
                                </xs:simpleType>
                            </xs:attribute>

                            <xs:attribute name="connection_fee" type="xs:double"/>
                            <xs:attribute name="available_until" type="xs:date"/>
                            <xs:attribute name="internet_traffic" type="xs:double" use="required"/>
                </xs:complexType>

</xs:schema>
```
