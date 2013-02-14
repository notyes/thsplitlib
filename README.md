thsplitlib
==========

Lib ตัดคำภาษาไทย สำหรับ PHP

How to use
==========

// Include Lib //
include(dirname(__FILE__) . DIRECTORY_SEPARATOR . 'THSplitLib/segment.php');
// New from Class Segment
  $segment = new Segment();
// Call Function get_segment_array()
  $result = $segment->get_segment_array("คำที่ต้องการตัด");
// ทดสอบ
  echo implode(' | ', $result);


คุณสามารถนำไปใช้ได้สำหรับทุก Web Application ทุกชนิดที่คุณต้องการ
แต่หากนำไปใช้เพื่อเชิงพานิชย์ กรุณา บอกเราด้วยครับที่ suwichalala@gmail.com

หากมีข้อสงสัย หรือ สอบถามสามารถแจ้งได้ที่ suwichalala@gmail.com
ขอบคุณครับ
