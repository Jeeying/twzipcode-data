# TwZipcode
�N���ضl�F(http://www.post.gov.tw/)��*�u�O�W�a�϶l���ϸ��e3�X�@���� 103/12(Excel��)�v*�ন�U�خ榡�A��K�n��}�o�ɥi�����ޥΡC

### ��Ƶ��c
| �Ѽ�    | ����           |
|---------|----------------|
| zipcode | 3�X�l���ϸ�    |
| county  | ���B���Ϊ��ҥ� |
| city    | �m����       |

### ��ƻ���

##### twzipcode-data.json
>json�HUNICODE�s�X�A�ά�[�w��](twzipcode-data.js.demo.html)

##### twzipcode-data.js
```javascript
/**
* ��Ʀs�bwindow.twzipcode
*/
var twzipcode = {

    /**
    *  �����C��  
    */
    "counties" : [
        "�O�_��", 
        ...
    ],
    
    /**
    *  �M��
    */
    "list" : [
            {'zipcode' : 100, 'county' : '�O�_��', 'city' : '������' },
            ...
    ],

    /**
    *  �̿��B���Ϊ��ҥ�����
    */
    "groupByCounty" : {
        "�O�_��": [
            {'zipcode' : 100, 'county' : '�O�_��', 'city' : '������' },
            ...
         ],
         "�򶩥�": [
         	{'zipcode' : 200, 'county' : '�򶩥�', 'city' : '���R��' },
            ...
         ],
         ...
    },
    
    /**
    *  �̶l���ϸ��@��key
    */
    "mapByZipcode" : {
        "100" : {'zipcode' : 100, 'county' : '�O�_��', 'city' : '������' },
        ...
    }
};
        
```
> json�HUNICODE�s�X�x�s�A��[�w��](twzipcode-data.js.demo.html)

##### twzipcode-data.csv
> csv�HUTF-8�s�X�x�s
