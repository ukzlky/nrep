<saw:report xmlns:saw="com.siebel.analytics.web/report/v1.1" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:sawx="com.siebel.analytics.web/expression/v1.1" xmlVersion="201201160">   
   <saw:criteria xsi:type="saw:simpleCriteria" subjectArea="&quot;SU_KALITE_ANALIZ&quot;" withinHierarchy="true">      
      <saw:columns>         
         <saw:column xsi:type="saw:regularColumn" columnID="c756360ed9af04730">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."YEDEK_CHAR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cecdad2020e99dc08">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."DURUMU"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec fontColor="#008000" fontStyle="bold" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec fontColor="#CC3333" fontStyle="bold" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">DEĞERLENDİRME DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec fontColor="#336699" fontStyle="bold" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEBİLİR</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec fontColor="#008000" fontStyle="bold" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEMEZ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#CC3333" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">İYİ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#336699" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF1</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#336699" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF2</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#008000" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF3</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#FF9933" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF4</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#CC3333" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#CC3333" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#336699" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#336699" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A2K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#008000" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#008000" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A3K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#FF9933" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cecdad2020e99dc08"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" fontColor="#FF9933" fontStyle="bold"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c53a283b7448403bd">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."SERBEST_KLOR_DURUMU"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SERBEST_KLOR_DURUMU_2</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1f85414fb25713b7">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">CAST("NUMUNELER"."SERBEST_KLOR_DEGERI" AS DOUBLE)</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" hAlign="center" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c53a283b7448403bd"/>                              
                              <sawx:expr xsi:type="xsd:string">DUSUK</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SERBEST KLOR DEGERI</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c779c08bdfae19190">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."SERBEST_KLOR_DURUMU"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SERBEST KLOR DURUMU</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c29589a42bc8a3e85">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ISLEM_TARIHI"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true">                  
                  <saw:dataFormat xsi:type="saw:custom" customFormat="DD/MM/YYYY"/></saw:formatSpec></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNE ALIS TARIHI</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="caec1a08bf8fb572e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ILCE_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>ILCE ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cfaa86a1530e42479">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."BINA_NO"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>BINA NO</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc344e1be53413f66">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."BLOK"</sawx:expr></saw:columnFormula></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3b451a327655292f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."DAIRE"</sawx:expr></saw:columnFormula></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c5e94d62022b58b3b">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ISIM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNE ALAN PERSONEL</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3bc170f2ab24ee26">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KAYNAK_NOKTA_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>KAYNAK NOKTA ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c38a01aa07b8b654f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KAYNAK_TUR_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>KAYNAK TUR ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c35a709303253000b">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KAYNAK_YER_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>KAYNAK YER ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf75349c9f7a1e8fb">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."MAHALLE_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>MAHALLE ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf9dd3931f5abbd78">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."SOKAK_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SOKAK ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf174f632698f781f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."MS_LINK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true">                  
                  <saw:dataFormat xsi:type="saw:number" commas="false" negativeType="minus" minDigits="0" maxDigits="0"/></saw:formatSpec></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat>               
               <saw:caption fmt="text">                  
                  <saw:text>MS LINK</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3d3ffd19480fc239">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."NUMUNE_KABUL_SAATI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNE KABUL SAATI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c11a923b8c8ede7c2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."TUR_ADI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>TUR ADI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c27eed1d6c8786739">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ALIS_SAATI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNE ALIS SAATI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc3ba0a7c049d7bfa">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."STANDART_OLMAYAN_SAYISI"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="repeat" hAlign="center" wrapText="true"/></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat>               
               <saw:caption fmt="text">                  
                  <saw:text>STANDART OLMAYAN SAYISI</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9f8092e403f75e01">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ADRES1"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>AÇIKLAMA1</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="caf258d23809c4728">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ADRES2"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>AÇIKLAMA2</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c79c05573e65eb487">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KALITE_NO"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>NUMUNELER</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>KALITE NO</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1e25c01b811390c4">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."SERBEST_KLOR_DURUMU"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9c64e1fae02e3dfc">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."T_GOSTERGE_DOZU_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ca7cf13795ee261d8">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_GOSTERGE_DOZU"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>524 TOPLAM_GOSTERGE_DOZU 0,10 mSv/yıl</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c426becee6c018727">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TRITYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cad4d08f587ce30d2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TRITYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>523 TRITYUM 100 bq/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc5b8668f2adc8201">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLOROFIL_A_429_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c852745cb81bcbf39">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."G_KIST_1000_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c6e9dbd0a200974a2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GIARDIA_KIST_100_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc30dc35b80667b15">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI_EMS_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ca92837f69f3d0fd7">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FLORÜR_214_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c856ead82daaa98c2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_KOLIFORM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c35d5a6ff0f339c54">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_KOLIFORM_KOB_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c7692ae9f37a8a215">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PH"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd704fb3183251d75"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd704fb3183251d75"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd704fb3183251d75"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd704fb3183251d75"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd704fb3183251d75"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd704fb3183251d75"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>100 ≤9,5-6,5≥ PH </saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd704fb3183251d75">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PH_VAL"</sawx:expr></saw:columnFormula></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd57110044a26667b">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BULANIKLIK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cf83fbbf1716de77b"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cf83fbbf1716de77b"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>101	BULANIKLIK NTU 1</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf83fbbf1716de77b">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BULANIKLIK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c7bd92c3b75ea0042">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_İLETKENLIK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c61d8c0b4b2a714cb">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_İLETKENLIK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c7bd92c3b75ea0042"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c7bd92c3b75ea0042"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c7bd92c3b75ea0042"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c7bd92c3b75ea0042"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>102	E.İLETKENLIK	25°C 2500 µS/cm</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1e890cb525e1fc19">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c24a9edaecea10329">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KOLIFORM_BAKTERI_VAL"</sawx:expr></saw:columnFormula></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3084d093bb985245">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_BAKTERI_SAYISI_22_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c2567bc9a51fc355f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_BAKTERI_SAYISI_35_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cea554e0b79bbcfb0">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_KOLIFORM_BAKTERI_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true" visibility="hidden"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb24eb49f349d4810">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALUMINYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c2f3664d285d8d060">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ARSENIK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cfa261911356179c3">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BARYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ccbb817afa0189d10">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KADMIYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c448907e57986be83">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KROM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="caa60623187d2a823">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CIVA_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="caa3d327802bf37ce">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SELENYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c0ec08b6a00dd3a8e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ANTIMON_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cab0092b827218023">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SODYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c18f5a79540e4fbf2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_ENTEROKOK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9ab62311abfcb9c1">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CLOSTRIDIUM_PERFRINGENS_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c6723e674eefe73f2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ENTEROKOKFEKAL_STREPTOKOK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb21caf13caca7b46">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_STREPTOKOK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cea811152e8fadeb5">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI_FEKAL_KOLIFORM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9b9a61f06747b14c">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BOR_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c003dfbbe32224598">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KOBALT_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3b5545db0b8f2673">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."C_OOKISTI_100_VAL"</sawx:expr></saw:columnFormula></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cfbca4e071f034bad">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."G_KIST_1000"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c21f8e36faf71e08a"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c21f8e36faf71e08a"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec wrapText="true" backgroundColor="#FF0000"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>510	GIARDIA KISTI 0 Kist/1000L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c143fc7b5f3301007">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GIARDIA_KIST_100"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c46222689f5575891"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c46222689f5575891"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF0000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>419 GIARDIA KISTI 0 Kist/100L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c2f52c87b899f1db5">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI_EMS"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>303 E.COLI EMS/100ml</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc9edcec4f0f672ed">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FLORÜR_214"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>214	FLORÜR mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ce85c2f563db704fc">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLOR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats/></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>103	SERBEST KLOR mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c02198031b4d611a8">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_KLOR"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>104	TOPLAM KLOR	mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1f77a00215aceb74">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."RENK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cac8b138a0936758f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."RENK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f77a00215aceb74"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f77a00215aceb74"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f77a00215aceb74"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f77a00215aceb74"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f77a00215aceb74"/>                              
                              <sawx:expr xsi:type="xsd:string">A2K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f77a00215aceb74"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>105	RENK 20 mg/L Pt-Co</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c431dc248e045e0e0">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GÖRÜNÜŞ"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>106	GÖRÜNÜŞ</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c63e569bc26285ffa">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."T_SERTLIK"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>200	T.SERTLIK mg/L CaCO₃</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c344ae6ffeca074c7">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."F_ALKALINITE"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>201	F.ALKALINITE	mg/L CaCO₃</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9589cf4517d93a06">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."M_ALKALINITE"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>202	M.ALKALINITE	mg/L CaCO₃</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cfe1ef72942810002">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."T_ALKALINITE"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>203	T.ALKALINITE	mg/L CaCO₃</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c5925a56e5a27a472">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">CASE   WHEN CAST("SU KALITE AYRINTI"."PH" AS DOUBLE)&lt;8.3 THEN     CAST("SU KALITE AYRINTI"."M_ALKALINITE" AS DOUBLE)*1.22   ELSE     ((CAST("SU KALITE AYRINTI"."F_ALKALINITE" AS DOUBLE)+CAST("SU KALITE AYRINTI"."M_ALKALINITE" AS DOUBLE))-2*CAST("SU KALITE AYRINTI"."M_ALKALINITE" AS DOUBLE))*1.22   END</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>204	BIKARBONAT	mg/L CaCO₃</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c39101bc2c9bc9b79">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SÜLFAT_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c0d7e4db786cfa837">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SÜLFAT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c39101bc2c9bc9b79"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c39101bc2c9bc9b79"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c39101bc2c9bc9b79"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c39101bc2c9bc9b79"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c39101bc2c9bc9b79"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>205	SÜLFAT 250 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cdddc9b479ea79340">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLORÜR_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c684e50efdac4234d">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLORÜR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdddc9b479ea79340"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdddc9b479ea79340"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdddc9b479ea79340"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>206	KLORÜR 250 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd24eb51b6f32a2f0">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."AMONYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>207	AMONYUM 0,5 mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c5e6ca03f5b640fb4">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NITRAT_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c8a976458a3e1bfd3">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NITRAT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c5e6ca03f5b640fb4"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c5e6ca03f5b640fb4"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c5e6ca03f5b640fb4"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>208	NITRAT 50 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c5fde774ca4afe147">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KALSIYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>209	KALSIYUM mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c7592ad5720ce770e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MAGNEZYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>210	MAGNEZYUM mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb57220cafe55a6b9">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DEMIR_VAL"</sawx:expr></saw:columnFormula></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3303bb1731e5a507">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DEMIR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">A2K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb57220cafe55a6b9"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>211	DEMIR 200 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c0314c72b5d2a439c">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."OKSITLENEBILIRLIK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ced5d074f2db8c091"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ced5d074f2db8c091"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>212	OKSITLENEBILIRLIK 5 mg/L O</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c404806fbe5a6eb68">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FLORÜR_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ceffb23963e978762">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FLORÜR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c404806fbe5a6eb68"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c404806fbe5a6eb68"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c404806fbe5a6eb68"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>213	FLORÜR 1,5 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1f74492b7444d9a5">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SIYANÜR_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1a1dd8ea2e09bdb0">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SIYANÜR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f74492b7444d9a5"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f74492b7444d9a5"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f74492b7444d9a5"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1f74492b7444d9a5"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>215	SIYANÜR 0,05	mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c4f2bb7b718c01bec">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FOSFAT_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c7112a064ea69c297">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FOSFAT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c4f2bb7b718c01bec"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>216	FOSFAT mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd79ede7a53c42352">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NITRIT_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c57f6a0795aa32f07">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NITRIT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd79ede7a53c42352"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cd79ede7a53c42352"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>217	NITRIT 0,5 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c6b5fcae53500e4e9">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BROMÜR"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>218	BROMÜR	mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb4d6fba3be19648d">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BROMAT_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ccaa6d67e2151c1e3">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BROMAT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb4d6fba3be19648d"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb4d6fba3be19648d"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>219	BROMAT	3 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c78353314fc28f13e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KURŞUN_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf85f561d49f07097">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KURŞUN"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c78353314fc28f13e"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c78353314fc28f13e"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c78353314fc28f13e"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>220	KURŞUN 10 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9af456802018bf51">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KADMIYUM_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ce495ed3e9be79f37">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KADMIYUM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9af456802018bf51"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9af456802018bf51"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>221	KADMIYUM 5 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c771966188f070823">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BAKIR_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true" visibility="hidden"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cbea564937b269a26">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BAKIR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c771966188f070823"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c771966188f070823"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c771966188f070823"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c771966188f070823"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c771966188f070823"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>222	BAKIR 2 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c034d896a4849f313">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ÇINKO_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ce3c0dd7ce750a0d5">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ÇINKO"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c034d896a4849f313"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>223	ÇINKO mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cac01fc7ef7f60b07">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MANGAN_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb498fd587893941f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MANGAN"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cac01fc7ef7f60b07"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cac01fc7ef7f60b07"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cac01fc7ef7f60b07"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cac01fc7ef7f60b07"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cac01fc7ef7f60b07"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cac01fc7ef7f60b07"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>224	MANGAN	50 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cdb1852f267cef47b">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NIKEL_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf53a90a0758e86e0">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NIKEL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdb1852f267cef47b"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdb1852f267cef47b"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdb1852f267cef47b"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdb1852f267cef47b"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cdb1852f267cef47b"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>225	NIKEL 20 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ce07b6db131d98486">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLOROFORM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>226	KLOROFORM	µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ca98af4abf6805ce3">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DIKLOROBROMOMETAN"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>227	DIKLOROBROMOMETAN	µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc2660a48fdedfdc8">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DIBROMOKLOROMETAN"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>228	DIBROMOKLOROMETAN	µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c879650a1897a1ec3">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BROMOFORM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>229	BROMOFORM	µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd021840fd3689796">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_KARBON_T_C_"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>230	TOPLAM KARBON (T.C.)	mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cdab07c2d4a1658ce">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."İNORGANIK_KARBON_I_C_"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>231	İNORGANIK KARBON (I.C.) mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c36663e4b1e753551">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_ORGANIK_KARBON_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd5b4da5cdb9e0c37">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_ORGANIK_KARBON"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c36663e4b1e753551"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c36663e4b1e753551"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c36663e4b1e753551"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>232	TOPLAM ORGANIK KARBON mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c6a242f0ca55c91fa">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."AMONYAK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c6d3a072994600bfe">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."AMONYAK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">A2K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">A3K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6a242f0ca55c91fa"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>235	AMONYAK 0,5mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cfbd8c838d3bdac04">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KOLIFORM_BAKTERI"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c24a9edaecea10329"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c24a9edaecea10329"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c24a9edaecea10329"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEBİLİR</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c24a9edaecea10329"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEMEZ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c24a9edaecea10329"/>                              
                              <sawx:expr xsi:type="xsd:string">İYİ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>300	TOPLAM KOLIFORM BAKTERI	0 kob/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c6d3c6a8ba86c1351">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1e890cb525e1fc19"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c1e890cb525e1fc19"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>301	E.COLI 0 kob/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c76f93d9dbcbc3f27">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_KOLIFORM_BAKTERI"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF1</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF2</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF3</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF4</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A2K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea554e0b79bbcfb0"/>                              
                              <sawx:expr xsi:type="xsd:string">A3K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>302	Toplam Koliform Bakteri 0 EMS/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c4a53b5078421e74e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_BAKTERI_SAYISI_35"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats/></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>304	TOPLAM BAKTERI SAYISI 35°C kob/mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd07ceaf2d44aea0e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_BAKTERI_SAYISI_22"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c3084d093bb985245"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c3084d093bb985245"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>305	TOPLAM BAKTERI SAYISI 22°C kob/mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c4a58d96a9d09103d">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALUMINYUM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb24eb49f349d4810"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb24eb49f349d4810"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb24eb49f349d4810"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb24eb49f349d4810"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb24eb49f349d4810"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>400	ALUMINYUM 200 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ce2ab0dc85a972588">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ARSENIK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c2f3664d285d8d060"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c2f3664d285d8d060"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c2f3664d285d8d060"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c2f3664d285d8d060"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>401	ARSENIK	10 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c0ac88b8ddcf664f2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BARYUM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cfa261911356179c3"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cfa261911356179c3"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>402	BARYUM mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb9f8aab93729effa">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KADMIYUM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ccbb817afa0189d10"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ccbb817afa0189d10"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ccbb817afa0189d10"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>403	KADMIYUM µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9e8f08b1f6610730">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KROM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c448907e57986be83"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c448907e57986be83"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c448907e57986be83"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c448907e57986be83"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>404	KROM 50 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c33cf095dea8ea07e">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CIVA"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa60623187d2a823"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa60623187d2a823"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa60623187d2a823"/>                              
                              <sawx:expr xsi:type="xsd:string">A1K</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa60623187d2a823"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa60623187d2a823"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>405	CIVA 1 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c999a16807794b39c">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SELENYUM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa3d327802bf37ce"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa3d327802bf37ce"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="caa3d327802bf37ce"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>406	SELENYUM 10 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c47b59ae4d85f9572">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GÜMÜŞ"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>407	GÜMÜŞ µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cec355a1240d2fc22">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ANTIMON"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c0ec08b6a00dd3a8e"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c0ec08b6a00dd3a8e"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>408	ANTIMON 5 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c011c264ac3a07da8">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BERILYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>409	BERILYUM µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c34d3a117cfa4a15f">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GROSS_ALFA"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>411  ALFA AKTİVİTESİ bq/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c517fe5a2fb4614a8">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GROSS_BETA"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>412  BETA AKTİVİTESİ bq/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c75ce003b9f2ec9f6">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_ÇÖZÜNMÜŞ_MADDE"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>415	TOPLAM ÇÖZÜNMÜŞ MADDE mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c890e738c6b32b8db">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."POTASYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>416	POTASYUM mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c19dff0cb080f1a34">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SODYUM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cab0092b827218023"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cab0092b827218023"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>417	SODYUM	200 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc84646692a18f2f9">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">null</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>418	KALSIYUM mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c96907c0e8820ed18">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FITOPLANKTON_SAYIMI"


</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>421	FITOPLANKTON SAYIMI	adet/mL  </saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9b2e57590d5de44a">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLOROFIL_A"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>422	KLOROFIL A mg/m³</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf07e5e6bef34bcdf">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MICROCYSTIN_LR"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>423	MICROCYSTIN LR ng/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1a0fc47e84d04011">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."LITYUM"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>424	LITYUM mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c7513968060c672f9">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_TRIHALOMETAN"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cf82a7d46865035da"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cf82a7d46865035da"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF0000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>425	TOPLAM TRIHALOMETAN 100 µg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c52efbdc70bc5daea">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_ENTEROKOK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c18f5a79540e4fbf2"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c18f5a79540e4fbf2"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>426	FEKAL ENTEROKOK	0 kob/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ca007a31f21f160f9">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_KOLIFORM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c856ead82daaa98c2"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c856ead82daaa98c2"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>427	FEKAL KOLIFORM 0 EMS/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c22e33998aa4be124">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">null</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>428	MAGNEZYUM mg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cacea75adc04a7bef">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KLOROFIL_A_429"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cc5b8668f2adc8201"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cc5b8668f2adc8201"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>429	KLOROFIL A	mg/m³</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cb212e74c2dca6aa8">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MIB"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>500	MIB	ng/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c9f6003a23cf9ad10">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GEOSMIN"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>501	GEOSMIN	ng/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c123d52cd1ff5f5c7">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."UV254"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>502	UV254	cm ¹</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c28d9b2d0ae9dea28">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALG_TOKSINLERI_LR"

</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>503	ALG TOKSINI (MİKROSİSTİN LR)	µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cfbfdc772086833b3">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALG_TOKSINLERI_LR_RRTAYINI"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>505	ALG TOKSINLERI(LR-RR)TAYINI	µg/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c1233c2197d666000">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SALMONELLA"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>506	SALMONELLA	var/yok/ L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c0d25ce902e35b8a4">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CLOSTRIDIUM_PERFRINGENS"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9ab62311abfcb9c1"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9ab62311abfcb9c1"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>507	CLOSTRIDIUM PERFRINGENS	0 kob/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd2af7c8a4bcf5b55">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SALMONELLA_SPP_"</sawx:expr></saw:columnFormula>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>508	SALMONELLA SPP.	var/yok/L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c16ef4a7dd353f723">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_KOLIFORM_KOB"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c35d5a6ff0f339c54"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEBİLİR</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c35d5a6ff0f339c54"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEMEZ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c35d5a6ff0f339c54"/>                              
                              <sawx:expr xsi:type="xsd:string">İYİ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>509	FEKAL KOLIFORM 0 kob/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cea52bd512be3e8ee">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ENTEROKOKFEKAL_STREPTOKOK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6723e674eefe73f2"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEBİLİR</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6723e674eefe73f2"/>                              
                              <sawx:expr xsi:type="xsd:string">GİRİLEMEZ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c6723e674eefe73f2"/>                              
                              <sawx:expr xsi:type="xsd:string">İYİ</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>513	ENTEROKOK(FEKAL STREPTOKOK) 0 kob/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c842af73eea15a3b1">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."FEKAL_STREPTOKOK"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb21caf13caca7b46"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb21caf13caca7b46"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb21caf13caca7b46"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cb21caf13caca7b46"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>514	FEKAL STREPTOKOK 0 EMS/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cd612c0ec804a0625">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI_FEKAL_KOLIFORM"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF1</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF2</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF3</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">SINIF4</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">A2Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">A3 DIŞI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="cea811152e8fadeb5"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>515	E.COLI (FEKAL KOLIFORM) 0 EMS/100mL</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c8a093f7483ad4d8c">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BOR"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9b9a61f06747b14c"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9b9a61f06747b14c"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c9b9a61f06747b14c"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>517	BOR 1 mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c36f320fb2ad54a35">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KOBALT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c003dfbbe32224598"/>                              
                              <sawx:expr xsi:type="xsd:string">A1Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#336699" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c003dfbbe32224598"/>                              
                              <sawx:expr xsi:type="xsd:string">A3Z</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF9933" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>518	KOBALT	mg/L</saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c108844ef281149d2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TAT"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c108844ef281149d2"/>                              
                              <sawx:expr xsi:type="xsd:string">Uygun</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="notEqual">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c108844ef281149d2"/>                              
                              <sawx:expr xsi:type="xsd:string">Uygun</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF0000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>521	TAT TKED   </saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c3795fbb5a8e52357">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."KOKU"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c3795fbb5a8e52357"/>                              
                              <sawx:expr xsi:type="xsd:string">Uygun</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="notEqual">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c3795fbb5a8e52357"/>                              
                              <sawx:expr xsi:type="xsd:string">Uygun</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#FF0000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>522	KOKU TKED   </saw:text></saw:caption>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c4980144447dec744">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALG_TOKSINLERI_LR_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c4e6bb8ddaeac45c2">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."E_COLI_EMS_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cf82a7d46865035da">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_TRIHALOMETAN_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c46222689f5575891">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."GIARDIA_KIST_100_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c21f8e36faf71e08a">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."G_KIST_1000_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ced5d074f2db8c091">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."OKSITLENEBILIRLIK_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="ceeaec8336b129ba4">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."C_OOKISTI_100_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="cc69d59704787df26">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."C_OOKISTI_100"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ceeaec8336b129ba4"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="ceeaec8336b129ba4"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat>               
               <saw:caption fmt="text">                  
                  <saw:text>420	Cryptosporidium Ookisti	Ookist/100L</saw:text></saw:caption></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c2d257a97d4f54183">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CRYPTOSPORIDIUM_OOKISTI_VAL"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true" visibility="hidden"/></saw:displayFormat>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>         
         <saw:column xsi:type="saw:regularColumn" columnID="c220ff6ce783a90ee">            
            <saw:columnFormula>               
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CRYPTOSPORIDIUM_OOKISTI"</sawx:expr></saw:columnFormula>            
            <saw:displayFormat>               
               <saw:formatSpec suppress="suppress" wrapText="true"/>               
               <saw:conditionalDisplayFormats>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c2d257a97d4f54183"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#008000" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat>                  
                  <saw:conditionalDisplayFormat>                     
                     <saw:formatRule>                        
                        <saw:condition>                           
                           <sawx:expr xsi:type="sawx:comparison" op="equal">                              
                              <sawx:expr xsi:type="sawx:columnRefExpr" columnID="c2d257a97d4f54183"/>                              
                              <sawx:expr xsi:type="xsd:string">STANDART DISI</sawx:expr></sawx:expr></saw:condition>                        
                        <saw:formatSpec backgroundColor="#CC3333" wrapText="true"/></saw:formatRule></saw:conditionalDisplayFormat></saw:conditionalDisplayFormats></saw:displayFormat>            
            <saw:tableHeading>               
               <saw:caption fmt="text">                  
                  <saw:text>SU KALITE AYRINTI</saw:text></saw:caption></saw:tableHeading>            
            <saw:columnHeading>               
               <saw:displayFormat>                  
                  <saw:formatSpec/></saw:displayFormat>               
               <saw:caption fmt="text">                  
                  <saw:text>511	Cryptosporidium Ookisti	Ookist/1000L</saw:text></saw:caption></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c36cc81d76532da79">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BENZOAPIREN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cb6d6f4b8dcd431a3">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BENZOAPIREN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c4ce118138822c0c8">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."INDENO_123_CDPIREN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c40222063a1019537">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."INDENO_123_CDPIREN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c630ad044f4c30e80">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DIAZINON_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c712f8683667078f7">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DIAZINON"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c9116318b20359541">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DISULFOTON_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c13cb573aae764a9f">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DISULFOTON"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c2344a12e28e243b6">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MALATHION_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c7a82873418787404">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."MALATHION"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ce8dad3a40048cc0b">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CHLORPYALFOS_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c38a187e1b531495a">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CHLORPYALFOS"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cc45b48d5484807be">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ETHION_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c5f1a63b5b69763f9">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ETHION"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cf42e42727773b918">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALDICARB_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ca09b90ceb881c671">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALDICARB"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ce36d405a376588fc">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALDICARB_SULFOXIDE_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ceeb564eca8286d09">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALDICARB_SULFOXIDE"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c3f5e275ac7f751c3">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALDICARB_SULFANE_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c359171299a5653b6">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ALDICARB_SULFANE"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c820f561379e1d22f">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."OXAMYL_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ce12933c36c8023f0">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."OXAMYL"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c86e3a434a441e9f8">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."METHOMYL_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c4a42859a5144a93c">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."METHOMYL"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c67058687e767ab99">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CARBOFURAN_3_HYDROXY_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c08bd287b34c23f91">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CARBOFURAN_3_HYDROXY"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c9b6a58fdd6f8bb1f">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CARBARYL_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c2901984e6b087674">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CARBARYL"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c936af6b759b5af9a">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CARBOFURAN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ce83402c2a2e3ad7e">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CARBOFURAN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c40dda5fcb105da4a">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PROPOXUR_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ced50f0dd3c011b71">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PROPOXUR"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c0d6b7627f027159e">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."METHIOCARB_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cddb352ec78373c89">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."METHIOCARB"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cff83388cf199a170">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ATRAZIN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c5c18e80055938d77">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."ATRAZIN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c90d9c0ebc514f148">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."METALAXYL_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c74ff78febc98e5c5">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."METALAXYL"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c95ed406d0817cf78">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DINICONOZADE_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c8ac1457acb05282f">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DINICONOZADE"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c7ffa454d47f764ee">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DEMETON_S_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c5054a2497813e60e">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DEMETON_S"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c796ca6c217303fae">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DEMETON_S_METHYL_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c6bc077afa0889d32">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."DEMETON_S_METHYL"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c87cd5681b9e79343">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CYPERMETHRIN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cee161116c0c29f32">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."CYPERMETHRIN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c5cf577b24474b398">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PERMETHRIN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c552910730232e57c">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PERMETHRIN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c4882c86a30c8b7c9">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SIMAZINE_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c8ecbf82165a7677c">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."SIMAZINE"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c5d4aa41fe0101a4e">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."T1245_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c07e9342c28a35761">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."T1245"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cf2a697b0f9d5baf2">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."D124_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ce4a794d462c6e436">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."D124"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="caa6b41cebe23554f">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NAPTHOL_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c093756171a65461e">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."NAPTHOL"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cecdaa14f5fa8c460">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."AKRILAMID_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c257ac1ec72a1b282">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."AKRILAMID"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ccf4d76c096e1864a">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BENZOBFLORANTEN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ceff581fe37e567a6">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BENZOBFLORANTEN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cbe72066316b78bd9">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BENZOGHIPERILEN_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c6e17837e5b602b63">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."BENZOGHIPERILEN"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c2ae8c857a4a14f7d">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_PESTISITLER_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="cdc372456b297b776">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."TOPLAM_PESTISITLER"</sawx:expr></saw:columnFormula></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="c87c057ec8fe4bf34">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PAH_VAL"</sawx:expr></saw:columnFormula>
            <saw:displayFormat>
               <saw:formatSpec visibility="hidden" suppress="suppress" wrapText="true"/></saw:displayFormat>
            <saw:columnHeading>
               <saw:displayFormat>
                  <saw:formatSpec/></saw:displayFormat></saw:columnHeading></saw:column>
         <saw:column xsi:type="saw:regularColumn" columnID="ccc9a73a92ae5ad23">
            <saw:columnFormula>
               <sawx:expr xsi:type="sawx:sqlExpression">"SU KALITE AYRINTI"."PAH"</sawx:expr></saw:columnFormula></saw:column></saw:columns>      
      <saw:filter>         
         <sawx:expr xsi:type="sawx:logical" op="and">            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KAYNAK_TUR_ADI"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KAYNAK_YER_ADI"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KAYNAK_NOKTA_ADI"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."TUR_ADI"</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."DURUMU"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."MS_LINK"</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ILCE_ADI"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."ISLEM_TARIHI"</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."KALITE_NO"</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."MAHALLE_ADI"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr>            
            <sawx:expr xsi:type="sawx:special" op="prompted" promptPrimarySubjectArea="&quot;SU_KALITE_ANALIZ&quot;">               
               <sawx:expr xsi:type="sawx:sqlExpression">"NUMUNELER"."SERBEST_KLOR_DURUMU"</sawx:expr>               
               <sawx:expr xsi:type="sawx:untypedLiteral">%</sawx:expr></sawx:expr></sawx:expr></saw:filter></saw:criteria>   
   <saw:views currentView="0">      
      <saw:view xsi:type="saw:compoundView" name="compoundView!1">         
         <saw:cvTable>            
            <saw:cvRow>               
               <saw:cvCell viewName="titleView!1">                  
                  <saw:displayFormat>                     
                     <saw:formatSpec/></saw:displayFormat></saw:cvCell></saw:cvRow>            
            <saw:cvRow>               
               <saw:cvCell viewName="tableView!1">                  
                  <saw:displayFormat>                     
                     <saw:formatSpec/></saw:displayFormat></saw:cvCell></saw:cvRow></saw:cvTable></saw:view>      
      <saw:view xsi:type="saw:titleView" name="titleView!1" includeName="false" startedDisplay="none"/>      
      <saw:view xsi:type="saw:tableView" name="tableView!1" scrollingEnabled="false">         
         <saw:edges>            
            <saw:edge axis="page" showColumnHeader="true">               
               <saw:edgeLayers/></saw:edge>            
            <saw:edge axis="section">               
               <saw:edgeLayers/></saw:edge>            
            <saw:edge axis="row" showColumnHeader="true">               
               <saw:edgeLayers>                  
                  <saw:edgeLayer type="column" columnID="c79c05573e65eb487"/>                  
                  <saw:edgeLayer type="column" columnID="c46222689f5575891"/>                  
                  <saw:edgeLayer type="column" columnID="cecdad2020e99dc08"/>                  
                  <saw:edgeLayer type="column" columnID="cc3ba0a7c049d7bfa"/>                  
                  <saw:edgeLayer type="column" columnID="c53a283b7448403bd"/>                  
                  <saw:edgeLayer type="column" columnID="c1f85414fb25713b7"/>                  
                  <saw:edgeLayer type="column" columnID="c779c08bdfae19190"/>                  
                  <saw:edgeLayer type="column" columnID="cf174f632698f781f"/>                  
                  <saw:edgeLayer type="column" columnID="c38a01aa07b8b654f"/>                  
                  <saw:edgeLayer type="column" columnID="c35a709303253000b"/>                  
                  <saw:edgeLayer type="column" columnID="c3bc170f2ab24ee26"/>                  
                  <saw:edgeLayer type="column" columnID="c11a923b8c8ede7c2"/>                  
                  <saw:edgeLayer type="column" columnID="c9f8092e403f75e01"/>                  
                  <saw:edgeLayer type="column" columnID="caf258d23809c4728"/>                  
                  <saw:edgeLayer type="column" columnID="caec1a08bf8fb572e"/>                  
                  <saw:edgeLayer type="column" columnID="cf75349c9f7a1e8fb"/>                  
                  <saw:edgeLayer type="column" columnID="cf9dd3931f5abbd78"/>                  
                  <saw:edgeLayer type="column" columnID="cc344e1be53413f66"/>                  
                  <saw:edgeLayer type="column" columnID="cfaa86a1530e42479"/>                  
                  <saw:edgeLayer type="column" columnID="c3b451a327655292f"/>                  
                  <saw:edgeLayer type="column" columnID="c5e94d62022b58b3b"/>                  
                  <saw:edgeLayer type="column" columnID="c29589a42bc8a3e85"/>                  
                  <saw:edgeLayer type="column" columnID="c27eed1d6c8786739"/>                  
                  <saw:edgeLayer type="column" columnID="c3d3ffd19480fc239"/>                  
                  <saw:edgeLayer type="column" columnID="c2567bc9a51fc355f"/>                  
                  <saw:edgeLayer type="column" columnID="cc5b8668f2adc8201"/>                  
                  <saw:edgeLayer type="column" columnID="c856ead82daaa98c2"/>                  
                  <saw:edgeLayer type="column" columnID="c4e6bb8ddaeac45c2" visibility="hidden"/>                  
                  <saw:edgeLayer type="column" columnID="c3b5545db0b8f2673" visibility="hidden"/>                  
                  <saw:edgeLayer type="column" columnID="ca92837f69f3d0fd7"/>                  
                  <saw:edgeLayer type="column" columnID="cf82a7d46865035da"/>                  
                  <saw:edgeLayer type="column" columnID="c6e9dbd0a200974a2"/>                  
                  <saw:edgeLayer type="column" columnID="c852745cb81bcbf39"/>                  
                  <saw:edgeLayer type="column" columnID="c35d5a6ff0f339c54"/>                  
                  <saw:edgeLayer type="column" columnID="cea554e0b79bbcfb0"/>                  
                  <saw:edgeLayer type="column" columnID="c24a9edaecea10329" visibility="hidden"/>                  
                  <saw:edgeLayer type="column" columnID="cd704fb3183251d75" visibility="hidden"/>                  
                  <saw:edgeLayer type="column" columnID="c7692ae9f37a8a215"/>                  
                  <saw:edgeLayer type="column" columnID="cf83fbbf1716de77b"/>                  
                  <saw:edgeLayer type="column" columnID="cd57110044a26667b"/>                  
                  <saw:edgeLayer type="column" columnID="c7bd92c3b75ea0042"/>                  
                  <saw:edgeLayer type="column" columnID="ced5d074f2db8c091"/>                  
                  <saw:edgeLayer type="column" columnID="c61d8c0b4b2a714cb"/>                  
                  <saw:edgeLayer type="column" columnID="ce85c2f563db704fc"/>                  
                  <saw:edgeLayer type="column" columnID="c02198031b4d611a8"/>                  
                  <saw:edgeLayer type="column" columnID="c1f77a00215aceb74"/>                  
                  <saw:edgeLayer type="column" columnID="cac8b138a0936758f"/>                  
                  <saw:edgeLayer type="column" columnID="c431dc248e045e0e0"/>                  
                  <saw:edgeLayer type="column" columnID="c39101bc2c9bc9b79"/>                  
                  <saw:edgeLayer type="column" columnID="c63e569bc26285ffa"/>                  
                  <saw:edgeLayer type="column" columnID="cdddc9b479ea79340"/>                  
                  <saw:edgeLayer type="column" columnID="c344ae6ffeca074c7"/>                  
                  <saw:edgeLayer type="column" columnID="c9589cf4517d93a06"/>                  
                  <saw:edgeLayer type="column" columnID="cfe1ef72942810002"/>                  
                  <saw:edgeLayer type="column" columnID="c5925a56e5a27a472"/>                  
                  <saw:edgeLayer type="column" columnID="c0d7e4db786cfa837"/>                  
                  <saw:edgeLayer type="column" columnID="c684e50efdac4234d"/>                  
                  <saw:edgeLayer type="column" columnID="cd24eb51b6f32a2f0"/>                  
                  <saw:edgeLayer type="column" columnID="c5e6ca03f5b640fb4"/>                  
                  <saw:edgeLayer type="column" columnID="c8a976458a3e1bfd3"/>                  
                  <saw:edgeLayer type="column" columnID="c5fde774ca4afe147"/>                  
                  <saw:edgeLayer type="column" columnID="c7592ad5720ce770e"/>                  
                  <saw:edgeLayer type="column" columnID="cb57220cafe55a6b9" visibility="hidden"/>                  
                  <saw:edgeLayer type="column" columnID="c3303bb1731e5a507"/>                  
                  <saw:edgeLayer type="column" columnID="c771966188f070823"/>                  
                  <saw:edgeLayer type="column" columnID="c0314c72b5d2a439c"/>                  
                  <saw:edgeLayer type="column" columnID="c404806fbe5a6eb68"/>                  
                  <saw:edgeLayer type="column" columnID="ceffb23963e978762"/>                  
                  <saw:edgeLayer type="column" columnID="cc9edcec4f0f672ed"/>                  
                  <saw:edgeLayer type="column" columnID="c1f74492b7444d9a5"/>                  
                  <saw:edgeLayer type="column" columnID="c1a1dd8ea2e09bdb0"/>                  
                  <saw:edgeLayer type="column" columnID="c4f2bb7b718c01bec"/>                  
                  <saw:edgeLayer type="column" columnID="c7112a064ea69c297"/>                  
                  <saw:edgeLayer type="column" columnID="cd79ede7a53c42352"/>                  
                  <saw:edgeLayer type="column" columnID="c57f6a0795aa32f07"/>                  
                  <saw:edgeLayer type="column" columnID="c6b5fcae53500e4e9"/>                  
                  <saw:edgeLayer type="column" columnID="cb4d6fba3be19648d"/>                  
                  <saw:edgeLayer type="column" columnID="ccaa6d67e2151c1e3"/>                  
                  <saw:edgeLayer type="column" columnID="c78353314fc28f13e"/>                  
                  <saw:edgeLayer type="column" columnID="cf85f561d49f07097"/>                  
                  <saw:edgeLayer type="column" columnID="c9af456802018bf51"/>                  
                  <saw:edgeLayer type="column" columnID="ce495ed3e9be79f37"/>                  
                  <saw:edgeLayer type="column" columnID="cbea564937b269a26"/>                  
                  <saw:edgeLayer type="column" columnID="c034d896a4849f313"/>                  
                  <saw:edgeLayer type="column" columnID="ce3c0dd7ce750a0d5"/>                  
                  <saw:edgeLayer type="column" columnID="cac01fc7ef7f60b07"/>                  
                  <saw:edgeLayer type="column" columnID="cb498fd587893941f"/>                  
                  <saw:edgeLayer type="column" columnID="cdb1852f267cef47b"/>                  
                  <saw:edgeLayer type="column" columnID="cf53a90a0758e86e0"/>                  
                  <saw:edgeLayer type="column" columnID="ce07b6db131d98486"/>                  
                  <saw:edgeLayer type="column" columnID="ca98af4abf6805ce3"/>                  
                  <saw:edgeLayer type="column" columnID="cc2660a48fdedfdc8"/>                  
                  <saw:edgeLayer type="column" columnID="c879650a1897a1ec3"/>                  
                  <saw:edgeLayer type="column" columnID="c21f8e36faf71e08a"/>                  
                  <saw:edgeLayer type="column" columnID="cd021840fd3689796"/>                  
                  <saw:edgeLayer type="column" columnID="cdab07c2d4a1658ce"/>                  
                  <saw:edgeLayer type="column" columnID="c36663e4b1e753551"/>                  
                  <saw:edgeLayer type="column" columnID="cd5b4da5cdb9e0c37"/>                  
                  <saw:edgeLayer type="column" columnID="c6a242f0ca55c91fa"/>                  
                  <saw:edgeLayer type="column" columnID="c6d3a072994600bfe"/>                  
                  <saw:edgeLayer type="column" columnID="cfbd8c838d3bdac04"/>                  
                  <saw:edgeLayer type="column" columnID="c1e890cb525e1fc19"/>                  
                  <saw:edgeLayer type="column" columnID="c6d3c6a8ba86c1351"/>                  
                  <saw:edgeLayer type="column" columnID="c76f93d9dbcbc3f27"/>                  
                  <saw:edgeLayer type="column" columnID="c2f52c87b899f1db5"/>                  
                  <saw:edgeLayer type="column" columnID="c4a53b5078421e74e"/>                  
                  <saw:edgeLayer type="column" columnID="cd07ceaf2d44aea0e"/>                  
                  <saw:edgeLayer type="column" columnID="c3084d093bb985245"/>                  
                  <saw:edgeLayer type="column" columnID="cb24eb49f349d4810"/>                  
                  <saw:edgeLayer type="column" columnID="c4a58d96a9d09103d"/>                  
                  <saw:edgeLayer type="column" columnID="c2f3664d285d8d060"/>                  
                  <saw:edgeLayer type="column" columnID="ce2ab0dc85a972588"/>                  
                  <saw:edgeLayer type="column" columnID="cfa261911356179c3"/>                  
                  <saw:edgeLayer type="column" columnID="c0ac88b8ddcf664f2"/>                  
                  <saw:edgeLayer type="column" columnID="ccbb817afa0189d10"/>                  
                  <saw:edgeLayer type="column" columnID="cb9f8aab93729effa"/>                  
                  <saw:edgeLayer type="column" columnID="c448907e57986be83"/>                  
                  <saw:edgeLayer type="column" columnID="c9e8f08b1f6610730"/>                  
                  <saw:edgeLayer type="column" columnID="caa60623187d2a823"/>                  
                  <saw:edgeLayer type="column" columnID="c33cf095dea8ea07e"/>                  
                  <saw:edgeLayer type="column" columnID="caa3d327802bf37ce"/>                  
                  <saw:edgeLayer type="column" columnID="c999a16807794b39c"/>                  
                  <saw:edgeLayer type="column" columnID="c47b59ae4d85f9572"/>                  
                  <saw:edgeLayer type="column" columnID="c0ec08b6a00dd3a8e"/>                  
                  <saw:edgeLayer type="column" columnID="cec355a1240d2fc22"/>                  
                  <saw:edgeLayer type="column" columnID="c011c264ac3a07da8"/>                  
                  <saw:edgeLayer type="column" columnID="c34d3a117cfa4a15f"/>                  
                  <saw:edgeLayer type="column" columnID="c517fe5a2fb4614a8"/>                  
                  <saw:edgeLayer type="column" columnID="c75ce003b9f2ec9f6"/>                  
                  <saw:edgeLayer type="column" columnID="c890e738c6b32b8db"/>                  
                  <saw:edgeLayer type="column" columnID="cab0092b827218023"/>                  
                  <saw:edgeLayer type="column" columnID="c19dff0cb080f1a34"/>                  
                  <saw:edgeLayer type="column" columnID="cc84646692a18f2f9"/>                  
                  <saw:edgeLayer type="column" columnID="c143fc7b5f3301007"/>                  
                  <saw:edgeLayer type="column" columnID="cc69d59704787df26"/>                  
                  <saw:edgeLayer type="column" columnID="c96907c0e8820ed18"/>                  
                  <saw:edgeLayer type="column" columnID="c9b2e57590d5de44a"/>                  
                  <saw:edgeLayer type="column" columnID="cf07e5e6bef34bcdf"/>                  
                  <saw:edgeLayer type="column" columnID="c1a0fc47e84d04011"/>                  
                  <saw:edgeLayer type="column" columnID="c1e25c01b811390c4"/>                  
                  <saw:edgeLayer type="column" columnID="c7513968060c672f9"/>                  
                  <saw:edgeLayer type="column" columnID="c4980144447dec744"/>                  
                  <saw:edgeLayer type="column" columnID="c18f5a79540e4fbf2"/>                  
                  <saw:edgeLayer type="column" columnID="c52efbdc70bc5daea"/>                  
                  <saw:edgeLayer type="column" columnID="ca007a31f21f160f9"/>                  
                  <saw:edgeLayer type="column" columnID="c22e33998aa4be124"/>                  
                  <saw:edgeLayer type="column" columnID="cacea75adc04a7bef"/>                  
                  <saw:edgeLayer type="column" columnID="cb212e74c2dca6aa8"/>                  
                  <saw:edgeLayer type="column" columnID="c9f6003a23cf9ad10"/>                  
                  <saw:edgeLayer type="column" columnID="c123d52cd1ff5f5c7"/>                  
                  <saw:edgeLayer type="column" columnID="c28d9b2d0ae9dea28"/>                  
                  <saw:edgeLayer type="column" columnID="cfbfdc772086833b3"/>                  
                  <saw:edgeLayer type="column" columnID="c1233c2197d666000"/>                  
                  <saw:edgeLayer type="column" columnID="c9ab62311abfcb9c1"/>                  
                  <saw:edgeLayer type="column" columnID="c0d25ce902e35b8a4"/>                  
                  <saw:edgeLayer type="column" columnID="cd2af7c8a4bcf5b55"/>                  
                  <saw:edgeLayer type="column" columnID="c16ef4a7dd353f723"/>                  
                  <saw:edgeLayer type="column" columnID="cfbca4e071f034bad"/>                  
                  <saw:edgeLayer type="column" columnID="c2d257a97d4f54183"/>                  
                  <saw:edgeLayer type="column" columnID="c220ff6ce783a90ee"/>                  
                  <saw:edgeLayer type="column" columnID="c6723e674eefe73f2"/>                  
                  <saw:edgeLayer type="column" columnID="cea52bd512be3e8ee"/>                  
                  <saw:edgeLayer type="column" columnID="cb21caf13caca7b46"/>                  
                  <saw:edgeLayer type="column" columnID="c842af73eea15a3b1"/>                  
                  <saw:edgeLayer type="column" columnID="cea811152e8fadeb5"/>                  
                  <saw:edgeLayer type="column" columnID="cd612c0ec804a0625"/>                  
                  <saw:edgeLayer type="column" columnID="c9b9a61f06747b14c"/>                  
                  <saw:edgeLayer type="column" columnID="c003dfbbe32224598"/>                  
                  <saw:edgeLayer type="column" columnID="c8a093f7483ad4d8c"/>                  
                  <saw:edgeLayer type="column" columnID="c36f320fb2ad54a35"/>                  
                  <saw:edgeLayer type="column" columnID="cc30dc35b80667b15"/>                  
                  <saw:edgeLayer type="column" columnID="c108844ef281149d2"/>                  
                  <saw:edgeLayer type="column" columnID="c3795fbb5a8e52357"/>                  
                  <saw:edgeLayer type="column" columnID="c426becee6c018727"/>                  
                  <saw:edgeLayer type="column" columnID="cad4d08f587ce30d2"/>                  
                  <saw:edgeLayer type="column" columnID="c9c64e1fae02e3dfc"/>                  
                  <saw:edgeLayer type="column" columnID="ca7cf13795ee261d8"/>                  
                  <saw:edgeLayer type="column" columnID="ceeaec8336b129ba4"/>                  
                  <saw:edgeLayer type="column" columnID="c756360ed9af04730"/>
                  <saw:edgeLayer type="column" columnID="c36cc81d76532da79"/>
                  <saw:edgeLayer type="column" columnID="cb6d6f4b8dcd431a3"/>
                  <saw:edgeLayer type="column" columnID="c4ce118138822c0c8"/>
                  <saw:edgeLayer type="column" columnID="c40222063a1019537"/>
                  <saw:edgeLayer type="column" columnID="c630ad044f4c30e80"/>
                  <saw:edgeLayer type="column" columnID="c712f8683667078f7"/>
                  <saw:edgeLayer type="column" columnID="c9116318b20359541"/>
                  <saw:edgeLayer type="column" columnID="c13cb573aae764a9f"/>
                  <saw:edgeLayer type="column" columnID="c2344a12e28e243b6"/>
                  <saw:edgeLayer type="column" columnID="c7a82873418787404"/>
                  <saw:edgeLayer type="column" columnID="ce8dad3a40048cc0b"/>
                  <saw:edgeLayer type="column" columnID="c38a187e1b531495a"/>
                  <saw:edgeLayer type="column" columnID="cc45b48d5484807be"/>
                  <saw:edgeLayer type="column" columnID="c5f1a63b5b69763f9"/>
                  <saw:edgeLayer type="column" columnID="cf42e42727773b918"/>
                  <saw:edgeLayer type="column" columnID="ca09b90ceb881c671"/>
                  <saw:edgeLayer type="column" columnID="ce36d405a376588fc"/>
                  <saw:edgeLayer type="column" columnID="ceeb564eca8286d09"/>
                  <saw:edgeLayer type="column" columnID="c3f5e275ac7f751c3"/>
                  <saw:edgeLayer type="column" columnID="c359171299a5653b6"/>
                  <saw:edgeLayer type="column" columnID="c820f561379e1d22f"/>
                  <saw:edgeLayer type="column" columnID="ce12933c36c8023f0"/>
                  <saw:edgeLayer type="column" columnID="c86e3a434a441e9f8"/>
                  <saw:edgeLayer type="column" columnID="c4a42859a5144a93c"/>
                  <saw:edgeLayer type="column" columnID="c67058687e767ab99"/>
                  <saw:edgeLayer type="column" columnID="c08bd287b34c23f91"/>
                  <saw:edgeLayer type="column" columnID="c9b6a58fdd6f8bb1f"/>
                  <saw:edgeLayer type="column" columnID="c2901984e6b087674"/>
                  <saw:edgeLayer type="column" columnID="c936af6b759b5af9a"/>
                  <saw:edgeLayer type="column" columnID="ce83402c2a2e3ad7e"/>
                  <saw:edgeLayer type="column" columnID="c40dda5fcb105da4a"/>
                  <saw:edgeLayer type="column" columnID="ced50f0dd3c011b71"/>
                  <saw:edgeLayer type="column" columnID="c0d6b7627f027159e"/>
                  <saw:edgeLayer type="column" columnID="cddb352ec78373c89"/>
                  <saw:edgeLayer type="column" columnID="cff83388cf199a170"/>
                  <saw:edgeLayer type="column" columnID="c5c18e80055938d77"/>
                  <saw:edgeLayer type="column" columnID="c90d9c0ebc514f148"/>
                  <saw:edgeLayer type="column" columnID="c74ff78febc98e5c5"/>
                  <saw:edgeLayer type="column" columnID="c95ed406d0817cf78"/>
                  <saw:edgeLayer type="column" columnID="c8ac1457acb05282f"/>
                  <saw:edgeLayer type="column" columnID="c7ffa454d47f764ee"/>
                  <saw:edgeLayer type="column" columnID="c5054a2497813e60e"/>
                  <saw:edgeLayer type="column" columnID="c796ca6c217303fae"/>
                  <saw:edgeLayer type="column" columnID="c6bc077afa0889d32"/>
                  <saw:edgeLayer type="column" columnID="c87cd5681b9e79343"/>
                  <saw:edgeLayer type="column" columnID="cee161116c0c29f32"/>
                  <saw:edgeLayer type="column" columnID="c5cf577b24474b398"/>
                  <saw:edgeLayer type="column" columnID="c552910730232e57c"/>
                  <saw:edgeLayer type="column" columnID="c4882c86a30c8b7c9"/>
                  <saw:edgeLayer type="column" columnID="c8ecbf82165a7677c"/>
                  <saw:edgeLayer type="column" columnID="c5d4aa41fe0101a4e"/>
                  <saw:edgeLayer type="column" columnID="c07e9342c28a35761"/>
                  <saw:edgeLayer type="column" columnID="cf2a697b0f9d5baf2"/>
                  <saw:edgeLayer type="column" columnID="ce4a794d462c6e436"/>
                  <saw:edgeLayer type="column" columnID="caa6b41cebe23554f"/>
                  <saw:edgeLayer type="column" columnID="c093756171a65461e"/>
                  <saw:edgeLayer type="column" columnID="cecdaa14f5fa8c460"/>
                  <saw:edgeLayer type="column" columnID="c257ac1ec72a1b282"/>
                  <saw:edgeLayer type="column" columnID="ccf4d76c096e1864a"/>
                  <saw:edgeLayer type="column" columnID="ceff581fe37e567a6"/>
                  <saw:edgeLayer type="column" columnID="cbe72066316b78bd9"/>
                  <saw:edgeLayer type="column" columnID="c6e17837e5b602b63"/>
                  <saw:edgeLayer type="column" columnID="c2ae8c857a4a14f7d"/>
                  <saw:edgeLayer type="column" columnID="cdc372456b297b776"/>
                  <saw:edgeLayer type="column" columnID="c87c057ec8fe4bf34"/>
                  <saw:edgeLayer type="column" columnID="ccc9a73a92ae5ad23"/></saw:edgeLayers></saw:edge>            
            <saw:edge axis="column" showColumnHeader="rollover"/></saw:edges></saw:view></saw:views></saw:report>
