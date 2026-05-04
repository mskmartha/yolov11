### 

yolo detect train data=/Users/smar602/Desktop/stockout/stockout/data.yaml \
    model=yolo26n.pt \
    imgsz=512 \
    epochs=60 \
    project=/Users/smar602/Desktop/stockout/yolov11/runs
    augment=True \
    optimizer=AdamW


yolo detect predict model=/Users/smar602/Desktop/stockout/yolov11/runs/train3/weights/best.pt source=/Users/smar602/Desktop/stockout/imgsafeway/safeway1.jpeg project=/Users/smar602/Desktop/stockout/yolov11/runs
